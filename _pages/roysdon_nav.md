---
layout: archive
title: "Projects"
permalink: /projects/roysdon_nav/
author_profile: true
---

{% include base_path %}

# Roysdon Nav Toolbox
<p align="center">
	<img width="500" img src="/images/navigation_toolbox2.png">
</p>


# Overview

## Navigation System Design, Estimation & Real-Time GNSS/INS Toolbox

The Roysdon Nav Toolbox is a state-of-the-art navigation engineering environment, built around optimal estimation theory and real-world sensor behavior. (*)

This toolbox supports centimeter-level navigation, full INS/GNSS mechanizations, and real-time embedded systems used for ground truth generation and deployed navigation stacks.


## What It Enables
- Design and validation of INS, GPS, GNSS, and multi-sensor navigation systems
- Industry-grade Bayesian estimation and smoothing
- Full sensor-error modeling and observability analysis
- Transition from simulation to real-time embedded navigation



<br><br>
# Toolboxes 

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



<br><br><br>
(*) This repo is a collection of tools from my personal research and publications.