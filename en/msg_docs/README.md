# uORB Message Reference

:::note
This list is [auto-generated](https://github.com/PX4/PX4-Autopilot/blob/master/msg/tools/generate_msg_docs.py) from the source code.
:::
    
This topic lists the UORB messages available in PX4 (some of which may be may be shared by the [PX4-ROS 2 Bridge](../ros/ros2_comm.md)).
Graphs showing how these are used [can be found here](../middleware/uorb_graph.md).
    
- [actuator_armed](actuator_armed.md)
- [actuator_controls](actuator_controls.md)
- [actuator_controls_status](actuator_controls_status.md)
- [actuator_outputs](actuator_outputs.md)
- [adc_report](adc_report.md)
- [airspeed](airspeed.md)
- [airspeed_validated](airspeed_validated.md)
- [airspeed_wind](airspeed_wind.md)
- [autotune_attitude_control_status](autotune_attitude_control_status.md)
- [battery_status](battery_status.md)
- [camera_capture](camera_capture.md)
- [camera_status](camera_status.md)
- [camera_trigger](camera_trigger.md)
- [cellular_status](cellular_status.md)
- [collision_constraints](collision_constraints.md) — Local setpoint constraints in NED frame
setting something to NaN means that no limit is provided
- [collision_report](collision_report.md)
- [commander_state](commander_state.md) — Main state, i.e. what user wants. Controlled by RC or from ground station via telemetry link.
- [control_allocator_status](control_allocator_status.md)
- [cpuload](cpuload.md)
- [debug_array](debug_array.md)
- [debug_key_value](debug_key_value.md)
- [debug_value](debug_value.md)
- [debug_vect](debug_vect.md)
- [differential_pressure](differential_pressure.md)
- [distance_sensor](distance_sensor.md) — DISTANCE_SENSOR message data
- [ekf2_timestamps](ekf2_timestamps.md) — this message contains the (relative) timestamps of the sensor inputs used by EKF2.
It can be used for reproducible replay.
- [ekf_gps_drift](ekf_gps_drift.md)
- [esc_report](esc_report.md)
- [esc_status](esc_status.md)
- [estimator_baro_bias](estimator_baro_bias.md)
- [estimator_event_flags](estimator_event_flags.md)
- [estimator_innovations](estimator_innovations.md)
- [estimator_optical_flow_vel](estimator_optical_flow_vel.md)
- [estimator_selector_status](estimator_selector_status.md)
- [estimator_sensor_bias](estimator_sensor_bias.md) — Sensor readings and in-run biases in SI-unit form. Sensor readings are compensated for static offsets,
scale errors, in-run bias and thermal drift (if thermal compensation is enabled and available).
- [estimator_states](estimator_states.md)
- [estimator_status](estimator_status.md)
- [estimator_status_flags](estimator_status_flags.md)
- [event](event.md) — Events interface
- [follow_target](follow_target.md)
- [generator_status](generator_status.md)
- [geofence_result](geofence_result.md)
- [gimbal_device_attitude_status](gimbal_device_attitude_status.md)
- [gimbal_device_information](gimbal_device_information.md)
- [gimbal_device_set_attitude](gimbal_device_set_attitude.md)
- [gimbal_manager_information](gimbal_manager_information.md)
- [gimbal_manager_set_attitude](gimbal_manager_set_attitude.md)
- [gimbal_manager_set_manual_control](gimbal_manager_set_manual_control.md)
- [gimbal_manager_status](gimbal_manager_status.md)
- [gps_dump](gps_dump.md) — This message is used to dump the raw gps communication to the log.
Set the parameter GPS_DUMP_COMM to 1 to use this.
- [gps_inject_data](gps_inject_data.md)
- [heater_status](heater_status.md)
- [home_position](home_position.md) — GPS home position in WGS84 coordinates.
- [hover_thrust_estimate](hover_thrust_estimate.md)
- [input_rc](input_rc.md)
- [internal_combustion_engine_status](internal_combustion_engine_status.md)
- [iridiumsbd_status](iridiumsbd_status.md)
- [irlock_report](irlock_report.md) — IRLOCK_REPORT message data
- [landing_gear](landing_gear.md)
- [landing_target_innovations](landing_target_innovations.md)
- [landing_target_pose](landing_target_pose.md) — Relative position of precision land target in navigation (body fixed, north aligned, NED) and inertial (world fixed, north aligned, NED) frames
- [led_control](led_control.md) — LED control: control a single or multiple LED's.
These are the externally visible LED's, not the board LED's
- [log_message](log_message.md) — A logging message, output with PX4_{WARN,ERR,INFO}
- [logger_status](logger_status.md)
- [mag_worker_data](mag_worker_data.md)
- [magnetometer_bias_estimate](magnetometer_bias_estimate.md)
- [manual_control_setpoint](manual_control_setpoint.md)
- [manual_control_switches](manual_control_switches.md)
- [mavlink_log](mavlink_log.md)
- [mission](mission.md)
- [mission_result](mission_result.md)
- [mount_orientation](mount_orientation.md)
- [multirotor_motor_limits](multirotor_motor_limits.md)
- [navigator_mission_item](navigator_mission_item.md)
- [obstacle_distance](obstacle_distance.md) — Obstacle distances in front of the sensor.
- [offboard_control_mode](offboard_control_mode.md) — Off-board control mode
- [onboard_computer_status](onboard_computer_status.md) — ONBOARD_COMPUTER_STATUS message data
- [optical_flow](optical_flow.md) — Optical flow in XYZ body frame in SI units.
http://en.wikipedia.org/wiki/International_System_of_Units
- [orb_test](orb_test.md)
- [orb_test_large](orb_test_large.md)
- [orb_test_medium](orb_test_medium.md)
- [orbit_status](orbit_status.md) — ORBIT_YAW_BEHAVIOUR
- [parameter_update](parameter_update.md) — This message is used to notify the system about one or more parameter changes
- [ping](ping.md)
- [position_controller_landing_status](position_controller_landing_status.md)
- [position_controller_status](position_controller_status.md)
- [position_setpoint](position_setpoint.md) — this file is only used in the position_setpoint triple as a dependency
- [position_setpoint_triplet](position_setpoint_triplet.md) — Global position setpoint triplet in WGS84 coordinates.
This are the three next waypoints (or just the next two or one).
- [power_button_state](power_button_state.md) — power button state notification message
- [power_monitor](power_monitor.md) — power monitor message
- [pwm_input](pwm_input.md)
- [px4io_status](px4io_status.md)
- [radio_status](radio_status.md)
- [rate_ctrl_status](rate_ctrl_status.md)
- [rc_channels](rc_channels.md)
- [rc_parameter_map](rc_parameter_map.md)
- [rpm](rpm.md)
- [rtl_flight_time](rtl_flight_time.md)
- [safety](safety.md)
- [satellite_info](satellite_info.md)
- [sensor_accel](sensor_accel.md)
- [sensor_accel_fifo](sensor_accel_fifo.md)
- [sensor_baro](sensor_baro.md)
- [sensor_combined](sensor_combined.md) — Sensor readings in SI-unit form.
These fields are scaled and offset-compensated where possible and do not
change with board revisions and sensor updates.
- [sensor_correction](sensor_correction.md) — Sensor corrections in SI-unit form for the voted sensor
- [sensor_gps](sensor_gps.md) — GPS position in WGS84 coordinates.
the field 'timestamp' is for the position & velocity (microseconds)
- [sensor_gyro](sensor_gyro.md)
- [sensor_gyro_fft](sensor_gyro_fft.md)
- [sensor_gyro_fifo](sensor_gyro_fifo.md)
- [sensor_mag](sensor_mag.md)
- [sensor_preflight_mag](sensor_preflight_mag.md) — Pre-flight sensor check metrics.
The topic will not be updated when the vehicle is armed
- [sensor_selection](sensor_selection.md) — Sensor ID's for the voted sensors output on the sensor_combined topic.
Will be updated on startup of the sensor module and when sensor selection changes
- [sensors_status_imu](sensors_status_imu.md) — Sensor check metrics. This will be zero for a sensor that's primary or unpopulated.
- [system_power](system_power.md)
- [takeoff_status](takeoff_status.md) — Status of the takeoff state machine currently just availble for multicopters
- [task_stack_info](task_stack_info.md) — stack information for a single running process
- [tecs_status](tecs_status.md)
- [telemetry_status](telemetry_status.md)
- [test_motor](test_motor.md)
- [timesync](timesync.md)
- [timesync_status](timesync_status.md)
- [trajectory_bezier](trajectory_bezier.md) — Bezier Trajectory description. See also Mavlink TRAJECTORY msg
The topic trajectory_bezier describe each waypoint defined in vehicle_trajectory_bezier
- [trajectory_waypoint](trajectory_waypoint.md) — Waypoint Trajectory description. See also Mavlink TRAJECTORY msg
The topic trajectory_waypoint describe each waypoint defined in vehicle_trajectory_waypoint
- [transponder_report](transponder_report.md)
- [tune_control](tune_control.md) — This message is used to control the tunes, when the tune_id is set to CUSTOM
then the frequency, duration are used otherwise those values are ignored.
- [uavcan_parameter_request](uavcan_parameter_request.md) — UAVCAN-MAVLink parameter bridge request type
- [uavcan_parameter_value](uavcan_parameter_value.md) — UAVCAN-MAVLink parameter bridge response type
- [ulog_stream](ulog_stream.md) — Message to stream ULog data from the logger. Corresponds to the LOGGING_DATA
mavlink message
- [ulog_stream_ack](ulog_stream_ack.md) — Ack a previously sent ulog_stream message that had
the NEED_ACK flag set
- [vehicle_acceleration](vehicle_acceleration.md)
- [vehicle_actuator_setpoint](vehicle_actuator_setpoint.md)
- [vehicle_air_data](vehicle_air_data.md)
- [vehicle_angular_acceleration](vehicle_angular_acceleration.md)
- [vehicle_angular_acceleration_setpoint](vehicle_angular_acceleration_setpoint.md)
- [vehicle_angular_velocity](vehicle_angular_velocity.md)
- [vehicle_attitude](vehicle_attitude.md) — This is similar to the mavlink message ATTITUDE_QUATERNION, but for onboard use
- [vehicle_attitude_setpoint](vehicle_attitude_setpoint.md)
- [vehicle_command](vehicle_command.md)
- [vehicle_command_ack](vehicle_command_ack.md)
- [vehicle_constraints](vehicle_constraints.md) — Local setpoint constraints in NED frame
setting something to NaN means that no limit is provided
- [vehicle_control_mode](vehicle_control_mode.md)
- [vehicle_global_position](vehicle_global_position.md) — Fused global position in WGS84.
This struct contains global position estimation. It is not the raw GPS
measurement (@see vehicle_gps_position). This topic is usually published by the position
estimator, which will take more sources of information into account than just GPS,
e.g. control inputs of the vehicle in a Kalman-filter implementation.
- [vehicle_gps_position](vehicle_gps_position.md) — GPS position in WGS84 coordinates.
the field 'timestamp' is for the position & velocity (microseconds)
- [vehicle_imu](vehicle_imu.md) — IMU readings in SI-unit form.
- [vehicle_imu_status](vehicle_imu_status.md)
- [vehicle_land_detected](vehicle_land_detected.md)
- [vehicle_local_position](vehicle_local_position.md) — Fused local position in NED.
The coordinate system origin is the vehicle position at the time when the EKF2-module was started.
- [vehicle_local_position_setpoint](vehicle_local_position_setpoint.md) — Local position setpoint in NED frame
setting something to NaN means the state should not be controlled
- [vehicle_magnetometer](vehicle_magnetometer.md)
- [vehicle_odometry](vehicle_odometry.md) — Vehicle odometry data. Fits ROS REP 147 for aerial vehicles
- [vehicle_rates_setpoint](vehicle_rates_setpoint.md)
- [vehicle_roi](vehicle_roi.md) — Vehicle Region Of Interest (ROI)
- [vehicle_status](vehicle_status.md) — If you change the order, add or remove arming_state_t states make sure to update the arrays
in state_machine_helper.cpp as well.
- [vehicle_status_flags](vehicle_status_flags.md) — This is a struct used by the commander internally.
- [vehicle_thrust_setpoint](vehicle_thrust_setpoint.md)
- [vehicle_torque_setpoint](vehicle_torque_setpoint.md)
- [vehicle_trajectory_bezier](vehicle_trajectory_bezier.md) — Vehicle Waypoints Trajectory description. See also MAVLink MAV_TRAJECTORY_REPRESENTATION msg
The topic vehicle_trajectory_bezier is used to send a smooth flight path from the
companion computer / avoidance module to the position controller.
- [vehicle_trajectory_waypoint](vehicle_trajectory_waypoint.md) — Vehicle Waypoints Trajectory description. See also MAVLink MAV_TRAJECTORY_REPRESENTATION msg
The topic vehicle_trajectory_waypoint_desired is used to send the user desired waypoints from the position controller to the companion computer / avoidance module.
The topic vehicle_trajectory_waypoint is used to send the adjusted waypoints from the companion computer / avoidance module to the position controller.
- [vtol_vehicle_status](vtol_vehicle_status.md) — VEHICLE_VTOL_STATE, should match 1:1 MAVLinks's MAV_VTOL_STATE
- [wheel_encoders](wheel_encoders.md)
- [wind](wind.md)
- [yaw_estimator_status](yaw_estimator_status.md)

    