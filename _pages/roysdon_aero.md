---
layout: archive
title: "Projects"
permalink: /projects/roysdon_aero/
author_profile: true
---

{% include base_path %}

# Roysdon Aero Toolbox
<p align="center">
	<img width="600" img src="/images/aircraft_design_toolbox2.png">
</p>

# Overview

## Aircraft Design, Flight Simulation & Real-Time Control Toolbox
The Roysdon Aero Toolbox is a full-stack aircraft and missile engineering environment, spanning conceptual design, high-fidelity simulation, flight controls, and embedded real-time software. (*)

## What It Enables
- Rapid aircraft and missile concept-to-simulation pipelines
- Linear and nonlinear 6-DOF flight dynamics
- Advanced guidance, navigation, and control (GNC) development
- Formation flight, intercepts, rockets, decoys, and recovery systems
- Transition from simulation to embedded flight software


<br><br>
# Toolboxes

## Simulation & Analysis
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


<br><br><br>
(*) This repo is a collection of tools from my personal research and publications.