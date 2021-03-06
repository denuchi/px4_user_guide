# 요약

* [소개](README.md)
* [시작하기](getting_started/README.md) 
  * [기본 개념](getting_started/px4_basic_concepts.md)
  * [기체/프레임](getting_started/frame_selection.md)
  * [비행 컨트롤러](getting_started/flight_controller_selection.md)
  * [센서](getting_started/sensor_selection.md)
  * [라디오 시스템](getting_started/rc_transmitter_receiver.md)
  * [비행 모드](getting_started/flight_modes.md)
  * [기체 상태 알림](getting_started/vehicle_status.md) 
    * [LED 의미](getting_started/led_meanings.md)
    * [소리 의미](getting_started/tunes.md)
    * [비행전 확인](flying/pre_flight_checks.md)
  * [비행 보고](getting_started/flight_reporting.md)
* [기본 조립](assembly/README.md) 
  * [비행 컨트롤러 설치](assembly/mount_and_orient_controller.md)
  * [진동 방지](assembly/vibration_isolation.md)
  * [CUAV V5+ 와이러링 빠른 시작](assembly/quick_start_cuav_v5_plus.md)
  * [CUAV V5 nano 와이러링 빠른시작](assembly/quick_start_cuav_v5_nano.md)
  * [Durandal 와이러링 빠른시작](assembly/quick_start_durandal.md)
  * [Pixhawk 4 와이러링 빠른시작](assembly/quick_start_pixhawk4.md)
  * [Pixhawk 4 Mini 와이러링 빠른시작](assembly/quick_start_pixhawk4_mini.md)
  * [Cube 와이러링 빠른시작](assembly/quick_start_cube.md)
  * [Pixracer 와이러링 빠른시작](assembly/quick_start_pixracer.md)
  * [Pixhawk 와이러링 빠른시작](assembly/quick_start_pixhawk.md)
* [기본 설정](config/README.md) 
  * [펌웨어:](config/firmware.md)
  * [기체](config/airframe.md)
  * [센서 방향 표정](config/flight_controller_orientation.md)
  * [나침반](config/compass.md)
  * [자이로스코프](config/gyroscope.md)
  * [가속계](config/accelerometer.md)
  * [대기 속력](config/airspeed.md)
  * [수평 수준 정렬](config/level_horizon_calibration.md)
  * [라디오 설정](config/radio.md)
  * [Joystick Setup](config/joystick.md)
  * [Flight Modes](config/flight_mode.md)
  * [Battery](config/battery.md)
  * [Safety](config/safety.md)
  * [Motors/Servos](config/motors.md)
* [기체 제작](airframes/README.md) 
  * [기체 프레임 참고문헌](airframes/airframe_reference.md)
  * [멀티콥터](frames_multicopter/README.md) 
    * [DJI F450 (CUAV v5+)](frames_multicopter/dji_f450_cuav_5plus.md)
    * [DJI F450 (CUAV v5 nano)](frames_multicopter/dji_f450_cuav_5nano.md)
    * [QAV250 (Pixhawk4 Mini)](frames_multicopter/holybro_qav250_pixhawk4_mini.md)
    * [X500 (Pixhawk 4)](frames_multicopter/holybro_x500_pixhawk4.md)
    * [S500 V2 (Pixhawk 4)](frames_multicopter/holybro_s500_v2_pixhawk4.md)
    * [DJI F450 + RTK \(Pixhawk 3 Pro\)](frames_multicopter/dji_flamewheel_450.md)
    * [QAV250 \(Pixhawk Mini\)](frames_multicopter/lumenier_qav250_pixhawk_mini.md)
    * [QAV250 \(Pixhawk/AUAV\_X2\)](frames_multicopter/lumenier_qav250_pixhawk_auav_x2.md)
    * [Spedix 250 \(Pixracer\)](frames_multicopter/spedix_s250_pixracer.md)
    * [Robocat 270 \(Pixracer\)](frames_multicopter/robocat_270_pixracer.md)
    * [Matrice 100 (Pixhawk 1)](frames_multicopter/matrice100.md)
    * [QAV-R 5" Racer (Pixracer)](frames_multicopter/qav_r_5_kiss_esc_racer.md)
  * [비행기](frames_plane/README.md) 
    * [Wing Wing Z84 \(Pixracer\)](frames_plane/wing_wing_z84.md)
  * [VTOL](frames_vtol/README.md) 
    * [FunCub QuadPlane (Pixhawk)](frames_vtol/vtol_quadplane_fun_cub_vtol_pixhawk.md)
    * [Ranger QuadPlane (Pixhawk)](frames_vtol/vtol_quadplane_volantex_ranger_ex_pixhawk.md)
    * [Convergence Tiltrotor (Pixfalcon)](frames_vtol/vtol_tiltrotor_eflite_convergence_pixfalcon.md)
    * [TBS Caipiroshka (Pixracer)](frames_vtol/vtol_tailsitter_caipiroshka_pixracer.md)
    * [Falcon Vertigo QuadPlane (Dropix)](frames_vtol/vtol_quadplane_falcon_vertigo_hybrid_rtf_dropix.md)
  * [로버](frames_rover/README.md) 
    * [Traxxas Stampede](frames_rover/traxxas_stampede.md)
* [비행](flying/README.md) 
  * [첫 비행을 위한 설명서 라인](flying/first_flight_guidelines.md)
  * [비행교실 101](flying/basic_flying.md) 
    * [착륙 \(고정익\)](flying/fixed_wing_landing.md)
  * [미션](flying/missions.md)
  * [지오펜스](flying/geofence.md)
  * [안전 포인트 계획하기](flying/plan_safety_points.md)
  * [비행 모드](flight_modes/README.md) 
    * [Position 모드 (MC)](flight_modes/position_mc.md)
    * [Altitude 모드 (MC)](flight_modes/altitude_mc.md)
    * [Manual/Stabilized 모드 (MC)](flight_modes/manual_stabilized_mc.md)
    * [Rattitude 모드 (MC)](flight_modes/rattitude_mc.md)
    * [Acro 모드 (MC)](flight_modes/acro_mc.md)
    * [Orbit 모드 (MC)](flight_modes/orbit.md)
    * [Position 모드 (FW)](flight_modes/position_fw.md)
    * [Altitude 모드 (FW)](flight_modes/altitude_fw.md)
    * [Stabilized 모드 (FW)](flight_modes/stabilized_fw.md)
    * [Acro 모드 (FW)](flight_modes/acro_fw.md)
    * [Manual 모드 (FW)](flight_modes/manual_fw.md)
    * [Takeoff 모드](flight_modes/takeoff.md)
    * [Land 모드](flight_modes/land.md)
    * [Return 모드](flight_modes/return.md)
    * [Hold 모드](flight_modes/hold.md)
    * [Mission 모드](flight_modes/mission.md)
    * [Follow Me 모드](flight_modes/follow_me.md)
    * [Offboard 모드](flight_modes/offboard.md)
  * [지형 따라가기/고정하기](flying/terrain_following_holding.md)
* [비행 로그 분석](log/flight_log_analysis.md) 
  * [비행 리뷰를 이용한 로그 분석](log/flight_review.md)
* [고급 속성](advanced_features/README.md) 
  * [RTK GPS](advanced_features/rtk-gps.md)
  * [정밀 착륙](advanced_features/precland.md)
  * [RockBlock SatCom 시스템](advanced_features/satcom_roadblock.md)
  * [항공 트래픽 회피: ADSB/FLARM](advanced_features/traffic_avoidance_adsb.md)
  * [항공 트래픽 회피: UTM](advanced_features/traffic_avoidance_utm.md)
  * [장애물 회피](computer_vision/obstacle_avoidance.md)
  * [안전 착륙](computer_vision/safe_landing.md)
  * [충돌 방지](computer_vision/collision_prevention.md)
  * [경로 계획 인터페이스](computer_vision/path_planning_interface.md)
* [고급 설정](advanced_config/README.md) 
  * [파라미터 찾기/갱신](advanced_config/parameters.md)
  * [멀티콥콥터 설정/조정](config_mc/README.md) 
    * [MC PID 조정 가이드](config_mc/pid_tuning_guide_multicopter.md)
    * [MC Setpoint 조정 (Trajectory 생성기)](config_mc/mc_trajectory_tuning.md) 
      * [MC Slew-rate 타입 Trajectory](config_mc/mc_slew_rate_type_trajectory.md)
      * [MC Jerk-limited 타입 Trajectory](config_mc/mc_jerk_limited_type_trajectory.md)
    * [멀티콥터 레이서 설정](config_mc/racer_setup.md)
  * [고정익 설정/조정](config_fw/README.md) 
    * [고정 PID 조정 설명서](config_fw/pid_tuning_guide_fixedwing.md)
    * [고정익 고급 튜닝 가이드](config_fw/advanced_tuning_guide_fixedwing.md)
    * [고정익 트리밍 가이드](config_fw/trimming_guide_fixedwing.md)
  * [VTOL 설정/조정](config_vtol/README.md) 
    * [QuadPlane 설정](config_vtol/vtol_quad_configuration.md)
    * [후방 이동 조정](config_vtol/vtol_back_transition_tuning.md)
    * [에어스피드 센서 없는 VTOL](config_vtol/vtol_without_airspeed_sensor.md)
    * [VTOL 날씨 풍향](config_vtol/vtol_weathervane.md)
  * [ESC 캘리브레이션](advanced_config/esc_calibration.md)
  * [ECL/EKF 개요 및 튜닝](advanced_config/tuning_the_ecl_ekf.md)
  * [비행 종류 설정](advanced_config/flight_termination.md)
  * [부트로더 업데이트](advanced_config/bootloader_update.md)
  * [Betaflight 시스템에 부트로더 플래싱 하기](advanced_config/bootloader_update_from_betaflight.md)
  * [지표 감지기 설정](advanced_config/land_detector.md)
  * [센서 온도 보정](advanced_config/sensor_thermal_calibration.md)
  * [고급 컨트롤러 방향](advanced_config/advanced_flight_controller_orientation_leveling.md)
  * [정적 압력 형성](advanced_config/static_pressure_buildup.md)
  * [사전시동/시동/시동끄기 설정](advanced_config/prearm_arm_disarm.md)
  * [전체 파라미터 참조](advanced_config/parameter_reference.md)
* [하드웨어 주변기기](peripherals/README.md) 
  * [시리얼 포트 설정](peripherals/serial_configuration.md)
  * [GPS/나침반](gps_compass/README.md) 
    * [RTK GPS](gps_compass/rtk_gps.md) 
      * [Hex Here+](gps_compass/rtk_gps_hex_hereplus.md)
      * [Drotek XL](gps_compass/rtk_gps_drotek_xl.md)
      * [CUAV C-RTK](gps_compass/rtk_gps_cuav_c-rtk.md)
      * [Trimble MB-Two](gps_compass/rtk_gps_trimble_mb_two.md)
      * [Hex Here2](gps_compass/rtk_gps_hex_here2.md)
      * [Freefly RTK GPS](gps_compass/rtk_gps_freefly.md)
  * [Telemetry Radios](telemetry/README.md) 
    * [SiK Radio](telemetry/sik_radio.md) 
      * [RFD900 (SiK) Telemetry Radio](telemetry/rfd900_telemetry.md)
      * [HKPilot (SIK) Telemetry Radio](telemetry/hkpilot_sik_radio.md)
      * [HolyBro (SIK) Telemetry Radio](telemetry/holybro_sik_radio.md)
    * [Telemetry Wifi](telemetry/telemetry_wifi.md) 
      * [ESP8266 WiFi 모듈](telemetry/esp8266_wifi_module.md)
      * [3DR Telemetry Wifi (단종)](telemetry/3dr_telemetry_wifi.md)
  * [MAVLink 텔레메트리 (OSD/GCS)](peripherals/mavlink_peripherals.md)
  * [FrSky 텔레메트리](peripherals/frsky_telemetry.md)
  * [전원 모듈](power_module/README.md) 
    * [CUAV HV pm](power_module/cuav_hv_pm.md)
    * [CUAV CAN PMU](power_module/cuav_can_pmu.md)
    * [Holybro PM07 (Pixhawk 4 PM)](power_module/holybro_pm07_pixhawk4_power_module.md)
    * [Holybro PM06 (Micro Power Module)](power_module/holybro_pm06_pixhawk4mini_power_module.md)
    * [Pomegranate 시스템 전원 모듈](power_module/pomegranate_systems_pm.md)
  * [거리 센서 \(레인지파인더\)](sensor/rangefinders.md) 
    * [Lightware SFxx 라이다](sensor/sfxx_lidar.md)
    * [uLanding 레이다](sensor/ulanding_radar.md)
    * [LeddarOne 라이다](sensor/leddar_one.md)
    * [Benewake TFmini 라이다](sensor/tfmini.md)
    * [Lidar-Lite](sensor/lidar_lite.md)
    * [TeraRanger](sensor/teraranger.md)
    * [Lanbao PSK-CM8JL65-CC5](sensor/cm8jl65_ir_distance_sensor.md)
  * [Tachometers (Revolution Counters)](sensor/tachometers.md) 
    * [ThunderFly TFRPM01 Tachometer Sensor](sensor/thunderfly_tachometer.md)
  * [Airspeed Sensors](sensor/airspeed.md)
  * [Optical Flow](sensor/optical_flow.md) 
    * [PX4FLOW](sensor/px4flow.md)
    * [PMW3901](sensor/pmw3901.md)
  * [ESCs & Motors](peripherals/esc_motors.md) 
    * [PWM ESCs and Servos](peripherals/pwm_escs_and_servo.md)
    * [DShot ESCs](peripherals/dshot.md)
    * [UAVCAN ESCs](peripherals/uavcan_escs.md)
  * [Camera](peripherals/camera.md)
  * [Parachute](peripherals/parachute.md)
  * [Companion Computer Peripherals](peripherals/companion_computer_peripherals.md)
  * [ADSB/FLARM (Traffic Avoidance)](peripherals/adsb_flarm.md)
* [오토파일럿 하드웨어](flight_controller/README.md) 
  * [Pixhawk 시리즈](flight_controller/pixhawk_series.md) 
    * [3DR Pixhawk 1 (FMUv2)](flight_controller/pixhawk.md)
    * [mRo Pixhawk (FMUv2)](flight_controller/mro_pixhawk.md)
    * [mRobotics-X2.1](flight_controller/mro_x2.1.md)
    * [HobbyKing HKPilot32 (FMUv2)](flight_controller/HKPilot32.md)
    * [Holybro Pixfalcon (FMUv2)](flight_controller/pixfalcon.md)
    * [Drotek Dropix (FMUv2)](flight_controller/dropix.md)
    * [mRo Pixracer (FMUv4)](flight_controller/pixracer.md)
    * [Hex Cube (Pixhawk 2) (FMUv3)](flight_controller/pixhawk-2.md)
    * [Drotek Pixhawk 3 Pro (FMUv4pro)](flight_controller/pixhawk3_pro.md)
    * [CUAV Pixhack v3 (FMUv3)](flight_controller/pixhack_v3.md)
    * [Holybro Pixhawk 4 (FMUv5)](flight_controller/pixhawk4.md)
    * [Holybro Pixhawk 4 Mini (FMUv5)](flight_controller/pixhawk4_mini.md)
    * [CUAV v5 (FMUv5)](flight_controller/cuav_v5.md)
    * [CUAV V5+ (FMUv5)](flight_controller/cuav_v5_plus.md)
    * [CUAV V5 nano (FMUv5)](flight_controller/cuav_v5_nano.md)
    * [3DR Pixhawk Mini (중단됨)](flight_controller/pixhawk_mini.md)
    * [AUAV-X2 (중단됨)](flight_controller/auav_x2.md)
    * [Silicon Errata](flight_controller/silicon_errata.md)
  * [(Air)Mind 시리즈](flight_controller/mind_series.md) 
    * [MindPX](flight_controller/mindpx.md)
    * [MindRacer](flight_controller/mindracer.md)
  * [Holybro Kakute F7](flight_controller/kakutef7.md)
  * [Holybro Durandal](flight_controller/durandal.md)
  * [Omnibus F4 SD](flight_controller/omnibus_f4_sd.md)
  * [ModalAI](flight_controller/modalai.md) 
    * [Flight Core v1](flight_controller/modalai_fc_v1.md)
  * [Snapdragon Flight](flight_controller/snapdragon_flight.md) 
    * [하드웨어 설정 예시](flight_controller/snapdragon_flight_hardware_example_setup.md)
    * [개발자 환경 설치](flight_controller/snapdragon_flight_dev_environment_installation.md)
    * [Snapdragon 소프트웨어 설치](flight_controller/snapdragon_flight_software_installation.md)
    * [설정](flight_controller/snapdragon_flight_configuration.md)
    * [Snapdragon 고급](flight_controller/snapdragon_flight_advanced.md)
  * [Raspberry Pi 2/3 Navio2](flight_controller/raspberry_pi_navio2.md)
  * [OcPoC-Zynq Mini](flight_controller/ocpoc_zynq.md)
  * [BeagleBone Blue](flight_controller/beaglebone_blue.md)
* [Complete Vehicles](complete_vehicles/README.md) 
  * [PX4 Vision Kit](complete_vehicles/px4_vision_kit.md)
  * [Crazyflie 2.0](complete_vehicles/crazyflie2.md)
  * [MindRacer BNF & RTF](complete_vehicles/mindracer_BNF_RTF.md) 
    * [MindRacer 210](complete_vehicles/mindracer210.md)
    * [NanoMind 110](complete_vehicles/nanomind110.md)
  * [BetaFPV Beta75X 2S Brushless Whoop](complete_vehicles/betafpv_beta75x.md)
  * [Holybro Kopis 2](complete_vehicles/holybro_kopis2.md)
  * [Intel® Aero RTF Drone (Discontinued)](complete_vehicles/intel_aero.md)
* [Development](development/development.md)

## Dronecode 관련 링크

* [PX4 개발자 설명서](https://dev.px4.io/master/en/)
* [QGroundControl 사용자 설명서](https://docs.qgroundcontrol.com/en/)
* [QGroundControl 개발자 설명서](https://dev.qgroundcontrol.com/en/)
* [MAVLink 설명서](https://mavlink.io/en/)
* [MAVSDK](https://mavsdk.mavlink.io/)
* [Dronecode 카메라 관리자](https://camera-manager.dronecode.org/en/)