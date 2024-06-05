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

Here'a a token to a demo account which contains routes. It's the same account that's used in [comma connect's](https://github.com/commaai/connect/blob/afd30e3e017331379743dcf590db167aa822ed9c/src/components/anonymous.jsx#L131) demo.
```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE3NDg1ODI0NjUsIm5iZiI6MTcxNzA0NjQ2NSwiaWF0IjoxNzE3MDQ2NDY1LCJpZGVudGl0eSI6IjBkZWNkZGNmZGYyNDFhNjAifQ.g3khyJgOkNvZny6Vh579cuQj1HLLGSDeauZbfZri9jw
```
