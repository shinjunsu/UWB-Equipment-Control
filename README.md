# UWB Equipment Control System

## Overview
C# 기반 UWB 안테나 조립 및 검사 장비제어 시뮬레이터 개발 프로젝트입니다.

## Equipment
- 6-Index Rotary Table
- 5 Jigs
- Loading / Waiting / Assembly / Vision / Unloading
- Virtual Servo X/Y/Z
- Sequence, I/O, Interlock, Alarm Simulation

## Solution Structure
- `UWB.Control`: Core equipment control logic
- `UWB.Simulator`: Console-based equipment simulator
- `UWB.Api`: Planned ASP.NET Core Web API
- `docs/`: Functional specifications and design documents

## Development Environment
- C# / .NET 8
- Visual Studio 2022

## Current Status
- [x] Solution and project setup
- [x] Project reference verification
- [ ] Equipment data models
- [ ] Station sequences
- [ ] Virtual I/O and motion
- [ ] API and Web HMI integration

## Notes
This is a software simulation project, not a validated physical machine safety controller.