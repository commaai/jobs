# comma.ai web challenge

[openpilot](https://github.com/commaai/openpilot) logs all sorts of interesting data as you drive, including GPS, IMU measurements, 20fps 360° video, all the CAN from the car, and [more](https://github.com/commaai/cereal/blob/master/log.capnp). Your goal is to build an interesting visualization for a user's openpilot routes.

All of the data openpilot logs is available in the [raw logs](https://github.com/commaai/openpilot/blob/master/system/loggerd/README.md), and the API serves the raw logs files and offers convenient endpoints for the log data used in [comma connect](https://connect.comma.ai).

The visualization can focus on any of the logged data, and it can be for a single route or multiple routes. Here’s an internal visualization as an example.

![mapviz](https://github.com/commaai/jobs/assets/8762862/15d224d0-75ca-4a80-bf47-2fbd7481ebed)

Your deliverable is a GitHub repo with the project.

NOTES
* keep the implementation simple
* use any data you want from the openpilot logs
* make sure to host the project on GitHub Pages
* API docs: https://api.comma.ai
* API JS client library: https://github.com/commaai/comma-api
* demo user account token: `TODO`
