# IEC 61850 GOOSE Communication on Linux

**A six-month professional project implementing IEC 61850 GOOSE communication in C on Linux at Innov-Alliance-Tech.**

| Project detail | Description |
|---|---|
| Language | C |
| Platform | Linux |
| Protocol | IEC 61850 GOOSE |
| Validation tools | libpcap and Wireshark |
| Duration | Six months |
| Context | Professional project at Innov-Alliance-Tech |

## Overview

This project focused on implementing an IEC 61850 GOOSE protocol stack in C on Linux.

GOOSE—Generic Object Oriented Substation Event—is used to exchange time-sensitive event information in electrical substation automation. The project combined low-level network programming, protocol implementation and communication validation.

## My Contribution

I implemented the protocol stack and evaluated its communication behaviour using packet capture and analysis tools.

The work required translating protocol requirements into a functioning implementation, investigating communication issues and checking the generated network traffic.

## Technical Focus

- IEC 61850 GOOSE communication
- Network programming in C on Linux
- Ethernet multicast communication
- Packet capture using libpcap
- Frame inspection and troubleshooting using Wireshark
- Communication latency evaluation

## Validation and Results

I used libpcap and Wireshark to capture and inspect the exchanged traffic and validate the implementation.

The project achieved communication latency below **4 ms under the tested conditions**. This result describes the project’s measurements; it is not a guarantee across all hardware, workloads or network environments.

## Skills Developed

- Implementing a specialised communication protocol
- Working with low-level networking in C
- Investigating Ethernet and multicast traffic
- Using packet captures to debug communication
- Evaluating timing requirements through practical measurements
- Connecting implementation decisions to observed system behaviour

## Reflection

This project strengthened my ability to move from protocol requirements to implementation and experimental validation.

It also developed my interest in industrial communication and cybersecurity. Understanding how operational messages are generated, transmitted and interpreted provides a foundation for investigating the security of industrial systems.

## Repository Scope

This repository currently provides a project overview. It does not contain source code, packet captures or detailed measurement records.
