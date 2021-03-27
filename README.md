# Tennis_Ball_Catching_Robot
Tennis Ball Catching Robot project -- Work in progress

-----

### Goal Steps
- [ ] Get Familiar with OpenCV basics
- [ ] Determine size and location of tennis ball in webcam feed
- [ ] Estimate Distance of tennis ball in webcam feed
- [ ] Generate XYZ position of tennis ball relative to camera
- [ ] Determine Velocity and Acceleration using XYZ position updates (Kalman Filter?) (acceleration not assumed to be gravity so that can account for ball spin???)
- [ ] Determine how accurate future position is based on N arguments
- [ ] Try to reduce the number of frames required to predict location
- [ ] Simulate Robot in ROS with camera telling it to reach target location
- [ ] Determine specs required to achieve speed (maybe desirable to toss up ball 5 ft, and catch within a tennis court half? not sure)
- [ ] Design robot to match specs
- [ ] Build robot to match specs
- [ ] Deploy ROS to robot and tune until it works in the real world
