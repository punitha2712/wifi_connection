# WiFi Connection using ESP32

## Project Description

This project demonstrates how to connect an ESP32 microcontroller to a WiFi network using the Wokwi online simulator.

## Objective

The main objective of this project is to establish a WiFi connection using ESP32 and display the connection status, IP address, and WiFi signal strength through the Serial Monitor.

## Components Used

* ESP32
* WiFi Network
* Wokwi ESP32 Simulator

## Software / Platform

* Arduino IDE
* Wokwi Online Simulator
* Arduino C/C++

## Working

The ESP32 uses the WiFi library to connect to the configured WiFi network. The program checks the WiFi connection status continuously until the connection is established.

After successful connection, the program displays:

* WiFi connection status
* Local IP address
* WiFi signal strength (RSSI)

The simulation can be tested directly using the Wokwi platform.

## Wokwi Simulation

[Click here to view and run the WiFi Connection Simulation](https://wokwi.com/projects/476467140466868225)

## How to Run

1. Open the Wokwi simulation using the link above.
2. Start the simulation.
3. Open the Serial Monitor.
4. The ESP32 attempts to connect to the WiFi network.
5. After successful connection, the connection status, IP address, and RSSI value are displayed.

## Project Outcome

The ESP32 successfully connects to the simulated WiFi network and displays the network information through the Serial Monitor.

## Security Note

This project uses the Wokwi guest network for simulation. Do not upload real WiFi passwords or other sensitive credentials to a public GitHub repository.
