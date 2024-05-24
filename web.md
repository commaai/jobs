# comma web challenge

[openpilot](https://github.com/commaai/openpilot) logs all sorts of interesting data as you drive, including GPS, IMU measurements, 20fps 360° video, all the CAN from the car, and [more](https://github.com/commaai/cereal/blob/master/log.capnp). Your goal is to build an interesting visualization for a user's openpilot routes.

All of the data openpilot logs is available in the [raw logs](https://github.com/commaai/openpilot/blob/master/system/loggerd/README.md),
and the API serves both the raw logs files and offers convenient endpoints for the log data used in [comma connect](https://connect.comma.ai).

Your deliverable is a GitHub repo with the project, plus a link to the GitHub Pages.
The visualization can focus on any of the logged data; think anything from comma connect to Spotify Wrapped.
Here’s an internal visualization as an example.

![mapviz](https://github.com/commaai/jobs/assets/8762862/15d224d0-75ca-4a80-bf47-2fbd7481ebed)

NOTES
* keep the implementation simple
* use any data you want from the openpilot logs
* API docs: https://api.comma.ai
* API JS client library: https://github.com/commaai/comma-api
* use https://jwt.comma.ai to get a token to authenticate with our API

Here's a list of public routes available for this challenge:
```
96850532278bae3b/000000dd--455f14369d
96850532278bae3b/000000cf--71260bfe89
96850532278bae3b/000000dc--64a114e596
96850532278bae3b/000000db--f3c1490349
96850532278bae3b/000000da--7f5ce1f9bd
96850532278bae3b/000000d8--62be50c081
96850532278bae3b/000000d7--c312e67d9a
96850532278bae3b/000000d4--529d0a2f8b
96850532278bae3b/000000d2--22576116b6
96850532278bae3b/000000d1--9e0f877e15
96850532278bae3b/000000d0--36a421cbfa
```
