# Autonomous Robotic Systems Assignment

University project for the course of Autonomous Robotic Systems on the design of a simulated mobile robot capable of navigating and mapping a 2D environment.

## Overview

The goal of the project is to build a robot simulation that integrates motion control, perception, localisation, mapping, and navigation. The robot operates in a simulated environment and keeps track of its position while exploring and interacting with obstacles.

The system was developed in multiple phases, progressively adding new capabilities.

## Main components

- Differential drive robot simulation with keyboard control  
- Infrared distance sensors for obstacle perception  
- Collision detection and handling  
- Position estimation using triangulation and a Kalman Filter  
- Occupancy grid mapping based on sensor readings  
- Autonomous navigation using planning algorithms  
- Multi-robot simulation in a shared environment  

## Structure

The implementation is organized into several modules, including:

- `Simulator.py` – manages the simulation and visualization  
- `Environment.py` – defines the environment and structures  
- `Robot.py` – motion model, triangulation, and system integration  
- `Sensor.py` – sensor simulation utilities  
- `Collision.py` – collision detection and response  
- `StandardKalmanFilter.py` – state estimation  
- `OccupancyGridMap.py` – 2D map updates from sensor data  
- `GeneticAlg.py` – autonomous navigation logic  
- `Main.py` – integrates all components  

## Context

This repository contains the code developed for a university assignment on autonomous robotic systems, focusing on simulation, localisation, mapping, and navigation in a 2D environment.

