# comma design challenge

openpilot is a level 2 system, and doesn't handle all driving situations.
openpilot is self-aware about how likely it is to make a mistake though.
The goal of this challenge is to convey openpilot's driving confidence states to the user while they are engaged.

We consider three main classes of driving output:
- pretty reliable, needs disengagement less than once every 10 min
- may or may not work, needs disengagement every few minutes or more
- expected to not work, will likely need disengagement within seconds

Note, there is a continuous spectrum across the classes providing the option to communicate it as an analog thing.

Additionally, the car has limits to how much torque on the steering wheel, brake pressure, and acceleration it can apply that depends on the specific car. openpilot knows how far it is from those limits. This is useful information for the user to know, and should be communicated in a clear non-intrusive way. Currently, openpilot throws an audible alert when it runs out of steering torque and starts deviating from the desired trajectory, which means the user can't know there is a problem until the alert, and the alert itself is frequently more annoying than useful.

NOTES
- The 3X presents unique design challenges as it is mostly used mounted to a windshield
- With our use of QT, a flat UI is enforced.
- Modify/design/change as much of the UI/UX experience of the device as you’d like.
- Sound may be included or alluded to in the work
- Take a look at the following videos (or search on your own) if you'd like to see more of openpilot and the comma hardware:
  - [https://www.youtube.com/watch?v=NhfjTfZpk_k](https://www.youtube.com/watch?v=NhfjTfZpk_k)
  - [https://www.youtube.com/watch?v=SUIZYzxtMQs&t=2s](https://www.youtube.com/watch?v=SUIZYzxtMQs&t=2s)