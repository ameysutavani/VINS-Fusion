# Developer Notes

## 2020-01-01:
* Added tello .yaml files.
* Tello IMU seems integrates large errors. One reason for this is slower IMU rate(~15Hz) than the camera(~30Hz). Drift reduces if camera is slowed to same rate as IMU.