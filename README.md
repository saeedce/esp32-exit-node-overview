# ESP32 WireGuard Exit Node

A small ESP32-based networking project that connects to an upstream Wi-Fi network and establishes a WireGuard tunnel to a MikroTik peer. It is designed to provide a managed egress path for traffic routed through the tunnel.

## Project overview

The ESP32 joins the configured Wi-Fi network, brings up its WireGuard interface, and forwards applicable traffic between the tunnel and the upstream network using network address translation. The firmware also includes connectivity recovery logic and LED indications for tunnel status and traffic activity.

## Highlights

- WireGuard connectivity to a MikroTik peer
- Wi-Fi uplink on ESP32
- Forwarding and NAT for routed tunnel traffic
- Periodic connectivity checks with recovery behavior
- LED status and traffic activity indication

## Scope of this repository

This repository contains a public project overview only. Firmware source code, installation files, private keys, credentials, and network-specific settings are maintained separately and are not included here.

## Hardware and software

- ESP32 development board
- ESP-IDF
- A configured MikroTik WireGuard peer
- An upstream Wi-Fi network

This project is intended as a personal networking and embedded-systems project. Adapt the configuration and routing to your own network before use.
