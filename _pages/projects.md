---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

This is a collection of projects from my **PhD research, MS research, and personal interests**.  


Note: **Most projects require a password to access the source code**, while others are free and open to the public.  This page is a **work in progress,** some projects are better documented than others.  I will clean this up as I have time to do so.



-----------------------------------------------------------------------------------
# RoysdonAero - Aircraft Design, Simulation, & Software Toolbox
<p align="center">
	<img width="600" img src="/images/aircraft_design_toolbox2.png">
</p>

## Simulation & Analysis
This repo is a collection of tools from my **personal and M.S./Ph.D. research and publications** on fixed-wing and rotary aircraft:
- [**Aero Analysis Spreadsheet**](https://github.com/pfroysdon/projects/blob/main/aerospace/aero_analysis_spreadsheet) is a complete aircraft design speadsheet including drag build-up, take-off analysis, structures analysis, turn performance, glide performance, and a complete aero-coefficient comparison to other aircraft.
- [**3 Degrees-of-Freedom (DOF) Aerial Decelerator**](https://github.com/pfroysdon/projects/blob/main/aerospace/3dof_decelerator) (parachute) used to simulate a parachute recovery footprint given an initial altitude, airspeed and wind conditions.
- [**6 DOF Flight Simulator - Linear**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_linear) implements classic control theory (PIDs) used for analyzing flight profiles and peformance of any aircraft.
- [**6 DOF Flight Simulator - Nonlinear**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_nonlinear) implements model predictive control (MPC) used for simulating nonlinear flight profiles.
- [**6 DOF Rocket Simulation**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_rocket) used for simulating flight profiles and peformance of any rocket.
- [**6 DOF Missile Intercept Simulation**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_missile_intercept) used for simulating flight profiles and peformance of missiles.
- [**6 DOF Trim-Condition Flight Simulator**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_trim) used for simulating linear trim state for a given flight condition.
- [**6 DOF Formation-Flight Simulator - Linear**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_formation_flight_linear) used for analyzing flight profiles and peformance of formation flight of multiple aircraft.
- [**6 DOF Formation-Flight Simulator - Nonlinear**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_formation_flight_nonlinear) used for analyzing flight profiles and peformance of formation flight of multiple aircraft.
- [**6 DOF Flight Sim with Command Filtered Backstepping Controller**](https://github.com/pfroysdon/projects/blob/main/aerospace/6dof_backstepping) implements modern control theory with full-nonlinear command filtered backstepping.
- [**32 Degrees-of-Freedom Aerial Towed Body**](https://github.com/pfroysdon/projects/blob/main/aerospace/32dof_towed_decoy) used to simulate an aerial towed body at various line lengths, altitude, airspeed and wind conditions.  The 32 DOF leverages the method of characteristics to model cable droop, cable harmonics, towed body aerodynamic characteristics, etc.  The transient effects of vehicle angluar changes and atmospheric perterbations are also modeled. 
- [**AVL batch**](https://github.com/pfroysdon/projects/blob/main/aerospace/avl_batch) performs a batch analysis of aero coefficients, using AVL, for use in a 6DOF sim.
- [**XFOIL batch**](https://github.com/pfroysdon/projects/blob/main/aerospace/xfoil_batch) performs a batch analysis of aero coefficients, using XFOIL, for use in a 6DOF sim.
- [**MDO**](https://github.com/pfroysdon/projects/blob/main/aerospace/mdo) performs a multi-disciplinary design optimization of an aircraft design.
- [**Wind Tunnel Data Analysis**](https://github.com/pfroysdon/projects/blob/main/aerospace/wind_tunnel_analysis) reduces raw wind tunnel data and converts the data into aerodynamic coefficients for a 6DOF flight simulator.
- [**Flight Data Analysis**](https://github.com/pfroysdon/projects/blob/main/aerospace/post_flight_analysis) reduces raw flight test telemetry and recorded data and converts the data into engineering units and plots the data in figures useful for post flight analysis.

## Real-time Software
- [**Autopilot - Classical Control Theory (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/aerospace/autopilot_classical) is real-time embedded software for guidance and control of a fixed-wing aircraft (standard wing, delta, flying wing), Helicopters, and multi-copters (bi, tri, quad, hexa, octa) using classical control theory.
- [**Autopilot - Modern Control Theory (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/aerospace/autopilot_modern) is real-time embedded software for guidance and control of a fixed-wing aircraft (standard wing, delta, or flying wing), using modern nonlinear backstepping control theory.
- [**Camera Gimbal (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/aerospace/camera_gimbal) is real-time embedded software to control a 2 or 3-axis camera stabalization gimbal.
- [**Antenna Tracker (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/aerospace/antenna_tracker) is a tool to generate both simulated and realtime azimuth and elevation servo commands for a narrow beam antenna gimbal to track an aircraft.
- [**On-screen Display (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/aerospace/on_screen_display) is real-time embedded software used to display real-time flight parameters to a heads-up-display.



-----------------------------------------------------------------------------------
# RoysdonCyber - Design, Simulation, & Software Toolbox
<p align="center">
	<img width="500" img src="/images/ILP_Lite_Main.png">
</p>

This repo is a collection of tools from **personal and Ph.D. research in mathematics and machine learning**:
- [**Cascaded AML**](https://github.com/pfroysdon/projects/blob/main/applied_math/cascaded_aml) performs an adversarial machine learning (AML) analysis using a cascaded algorithm.
- [**ilpLite**](https://github.com/pfroysdon/projects/blob/main/applied_math/ilp_lite) is a complete implementation of integer linear programming for network analysis.
- [**JPDAF**](https://github.com/pfroysdon/projects/blob/main/applied_math/jpdaf) is a complete implementation of a joint-probability data-association filter (JPDAF); basically a cascaded EKF for object tracking.
- [**Network Flow**](https://github.com/pfroysdon/projects/blob/main/applied_math/network_flow) performs a network flow anaysis using ilpLite.
- [**OFDM**](https://github.com/pfroysdon/projects/blob/main/applied_math/ofdm) is an advanced sim for othogonal frequency division multiplexing.



-----------------------------------------------------------------------------------
# RoysdonNav - Navigation System Design, Simulation, & Software Toolbox
<p align="center">
	<img width="500" img src="/images/navigation_toolbox2.png">
</p>

This repo is a collection of tools from my **personal and Ph.D. research and publications**:

## Simulation & Analysis
- [**AHRS State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/ahrs_state_estimation) is a complete implementation of an attitude heading and reference system.
- [**Allan Variance**](https://github.com/pfroysdon/projects/blob/main/navigation/allan_variance) is a complete implementation of an Allan-Variance analysis.
- [**Baro Temporal Propagation & State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/baro_temporal_propagation) is a complete implementation of a baro-altitude temporal propagation algorithm.
- [**Covariance Analysis**](https://github.com/pfroysdon/projects/blob/main/navigation/covariance) is a complete implementation of a covariance analysis to select parameters to estimate in a state estimation filter.
- [**Full-nonlinear Optimal Bayesian State Estimation (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/navigation/crt_nav) is a complete GPS-aided INS nav that implements a *state-of-the-art full-nonlinear optimal Bayesian navigation system*. This system is highly flexible with selectable states (GPS loosely-coupled, GPS tightly-coupled, GPS single-differencing, GPS double-differencing, baro-aiding), selectable initialization modes, selectable mechanization (NED, wander-azimuthm, ECEF, ECI), and IMU errros (bias, scale factor, quantiization)
- [**Trajectory Smoother &  State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/crt_traj_smoother) this tool performs a full nonlinear optimization to smooth a trajectory using INS and GPS to an accuracy of 1 meter in position.
- [**Trajectory Smoother&  State Estimation with Integers**](https://github.com/pfroysdon/projects/blob/main/navigation/crt_traj_smoother_integers) this tool performs a full nonlinear optimization to smooth a trajectory using INS and L1/L2 GPS to an *accuracy of 1 centimeter* in position.  *This is used for generating ground-truth in my scientific publications.*
- [**EKF GPS State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/ekf_gps) is a complete implementation of an extended Kalman filter (EKF) for a GPS receiver with selectable 5, 8, and 11-states.
- [**EKF GPS-INS State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/ekf_gps_ins) is a complete implementation of an EKF for a GPS-aided inertial navigation system (INS).  This system is highly flexible with selectable states (GPS loosely-coupled, GPS tightly-coupled, GPS single-differencing, GPS double-differencing, baro-aiding), selectable initialization modes, selectable mechanization (NED, wander-azimuthm, ECEF, ECI), and IMU errros (bias, scale factor, quantiization).
- [**EKF IMU zero-update**](https://github.com/pfroysdon/projects/blob/main/navigation/ekf_imu_zero_update) is a complete implementation of an EKF performing zero-updates (velocity or angular rate) of an IMU.  This is used to evaluate the real-time performance of IMU accel-bias and gyro-bias parameters.
- [**GPS Positioning & State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/gps_positioning) is a complete implementation of GPS positioning system using pseudo-range, doppler and phase on both L1 and L2 frequencies for precise positioning.
- [**IMU Coning & Sculling**](https://github.com/pfroysdon/projects/blob/main/navigation/imu_coning_sculling) calculates the coning and sculling errors of an IMU.
- [**IMU Divergence**](https://github.com/pfroysdon/projects/blob/main/navigation/imu_divergence) evaluates the divergence and covariance of several different grades of IMU's.
- [**INS Alignment**](https://github.com/pfroysdon/projects/blob/main/navigation/ins_alignment) is a complete implementation of INS alignment routines.
- [**INS Error Comparison**](https://github.com/pfroysdon/projects/blob/main/navigation/ins_error_comp) evaluates the errors of several different grades of IMU's.
- [**INS Error Sensitivity**](https://github.com/pfroysdon/projects/blob/main/navigation/ins_error_sensitivity) evaluates the error sensitivity of several different grades of IMU's given a trajectory.
- [**INS Temporal Propagation**](https://github.com/pfroysdon/projects/blob/main/navigation/ins_temporal_propagation) is a complete implementation of an INS temporal propagation algorithm in with selectable mechanization (NED, wander-azimuthm, ECEF, ECI).
- [**Mag Calibration**](https://github.com/pfroysdon/projects/blob/main/navigation/mag_calibration) is a complete implementation of a 3-axis magnetometer calibration.
- [**Mag Temporal Propagation & State Estimation**](https://github.com/pfroysdon/projects/blob/main/navigation/mag_temporal_propagation) is a complete implementation of a 3-axis magnetometer temporal propagation.
- [**Monte Carlo**](https://github.com/pfroysdon/projects/blob/main/navigation/monte_carlo) is a complete MonteCarlo analysis toolbox for evaluating EKF and CRT performance. 
- [**ReFrame GUI**](https://github.com/pfroysdon/projects/blob/main/navigation/reframe) is a GUI to load attitude data from a .CSV and transform the reference frame from NED to ECEF or ECI.  This is used for visual inspection of robotics data with an unknown reference frame definition.
- [**Signal Generator**](https://github.com/pfroysdon/projects/blob/main/navigation/signal_generator) is a complete implementation of a 3DOF/6DOF trajectory generator and a signal generator for several sensors (GPS, IMU, baro, mag, sonar, radar, and signals of opportunity).
- [**3DOF/6DOF Trajectory Generator**](https://github.com/pfroysdon/projects/blob/main/navigation/tragetory_generator) is a complete implementation of a trajectory generator for both air and land vehicles.  This tool implements both a kinematics model capable of any trajectory, and an F-16 6DOF model capable of advanced aerial profiles with realistic autopilot feed-back loops (this uses the NASA F-16 6DOF model parameters).
- [**Real-time Kinematic (RTK) GNSS**](https://github.com/pfroysdon/projects/blob/main/navigation/rtk) is a complete implementation of an Real-time Kinematic (RTK) GNSS toolbox that leverages multiple GNSS constellations and solves L1/L2 integer ambiguity for centimeter-level ground truth. 


## Real-time Software
- [**CRT-LSS Nav (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/navigation/crt_nav) is a complete GPS-aided INS nav that implements a *state-of-the-art full-nonlinear optimal Bayesian navigation system*. This system is highly flexible with selectable states (GPS loosely-coupled, GPS tightly-coupled, GPS single-differencing, GPS double-differencing, baro-aiding), selectable initialization modes, selectable mechanization (NED, wander-azimuthm, ECEF, ECI), and IMU errros (bias, scale factor, quantiization)
- [**Data Acquisition System (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/navigation/daq) is a complete implementation of data acquisition system with GPS, IMU, Mag, and 20 A2D channels.
- [**RTK (Software & GUI)**](https://github.com/pfroysdon/projects/blob/main/navigation/rtk) is a complete implementation of a real-time kinematic GPS positioning system using both a base station and rover for 1 cm level positioning.


## Data Parsers
- [**Data Parser CRT-LSS**](https://github.com/pfroysdon/projects/blob/main/navigation/parser_crt) parses the binary messages generated from real-time CRT navigation system.
- [**Data Parser NovAtel**](https://github.com/pfroysdon/projects/blob/main/navigation/parser_novatel) parses the binary messages generated from a real-time NovAtel GPS system.
- [**Data Parser uBlox**](https://github.com/pfroysdon/projects/blob/main/navigation/parser_ublox) parses the binary messages generated from a real-time uBlox GPS system.


-----------------------------------------------------------------------------------
# Musings
This repo is a collection of random projects:
- [**Garden Bot**](https://github.com/pfroysdon/projects/blob/main/musings/garden_bot) is a real-time embedded software for a garden irrigation system.
- [**Package Shaker**](https://github.com/pfroysdon/projects/blob/main/musings/package_shaker) is a real-time embedded software for a "Gag Gift" that, when triggered, either shakes a package, sounds a siren or plays a melody.
- [**Greenhouse**](https://github.com/pfroysdon/projects/blob/main/musings/greenhouse) is a complete build guide with blueprints for 10'x12' floating panel greenhouse that can be built using common tools and materials sourced from any home-improvement store.



-----------------------------------------------------------------------------------
# RoysdonWatchCo
This repo is a collection of tools for **watchmakers**:
- [**Beat Rate**](https://github.com/pfroysdon/projects/blob/main/watchmaker/beat_rate) this tool uses recorded audio of a mechanical watch to determine the beat rate and phase of the balance.  Beat error results in a watch running fast or slow.  This enables the precise adjustment of a mechanical watch to reduce beat error. 
- [**Guilloche CAD/CAM**](https://github.com/pfroysdon/projects/blob/main/watchmaker/guilloche) this toolbox generates complex geometric patterns for wrist watch dials, and then generates the tool paths and g-code (machine code) for use on a CNC mill.
- [**Hairspring Calculations**](https://github.com/pfroysdon/projects/blob/main/watchmaker/hairspring) This project contains a complete report of the equations, derivations and unit conversion to calculate the length of a hairspring for any material, thickness, and height.  A spreadsheet "calculator" is also provided, to automatically calculate the length given a few input parameters.
- [**Laser Settings**](https://github.com/pfroysdon/projects/tree/main/watchmaker/laser_testing) this repository contains laser test files and examples for a JPT 50W fiber laser.