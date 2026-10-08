# Appsource-Spiri-Simulation

SpiriConfig apps for simulating Spiri robots: the world, the robots, and the
apps that stand in for hardware inside a simulated robot. Images are built by
[SpiriDevelopmentKit](https://github.com/spiri-robotics/SpiriDevelopmentKit).

| App | Runs on | What it is |
| --- | --- | --- |
| `zenoh-router` | the appliance | The router everything meets at. Install first. |
| `gazebo` | the appliance | Gazebo Jetty world plus a browser viewer |

A simulated Mu also installs from Appsource-Spiri-Mu, just without its
ArduPilot and camera connectors.

Add it to SpiriConfig:

```console
$ export SPIRICONFIG_APPSTORE_STORES='["https://github.com/spiri-robotics/Appsource-Spiri-Simulation"]'
$ spiriconfig appstore install zenoh-router
$ spiriconfig appstore install gazebo
```
