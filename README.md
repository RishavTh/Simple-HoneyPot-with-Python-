# Simple Honeypot Using Python

This project implements a basic TCP honeypot using Python. It listens on a specified port and logs connection attempts, simulating a fake service. The honeypot is designed for educational and testing purposes to demonstrate how unauthorized access attempts can be detected in a controlled environment.

## Features

- Listens for incoming TCP connections on a custom port
- Logs the source IP address and port of each connection
- Sends a fake "Access Denied" message to the client
- Lightweight and easy to set up
- Compatible with tools like Nmap and Netcat for testing

## Requirements

- Python 3.x
- Linux (recommended)
- Optional testing tools:
  - Nmap
  - Netcat

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/simple-honeypot.git
   cd simple-honeypot
