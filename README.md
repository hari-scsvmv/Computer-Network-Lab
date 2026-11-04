# Computer Networks Laboratory

A structured collection of **Computer Networks (CN) laboratory experiments** covering network configuration, connectivity testing, packet inspection, DNS, TCP/UDP socket programming, ARP/RARP, and routing simulations using **NS-2**.

## Experiment index

| No. | Experiment | File |
|---:|---|---|
| 01 | Network commands and packet analysis | [Experiment 01](<Experiment 01 - Network Commands and Packet Analysis.txt>) |
| 02 | Machine hostname and IP address using Python | [Experiment 02](<Experiment 02 - Machine Hostname and IP Address.py>) |
| 03 | HTTP client/server using TCP sockets | [Experiment 03](<Experiment 03 - HTTP Web Client and Server using TCP Sockets.py>) |
| 04 | TCP echo client and server | [Experiment 04](<Experiment 04 - TCP Echo Client and Server.py>) |
| 05 | TCP multi-client chat application | [Experiment 05](<Experiment 05 - TCP Multi-Client Chat Application.py>) |
| 06 | TCP file transfer | [Experiment 06](<Experiment 06 - TCP File Transfer.py>) |
| 07 | ARP and RARP protocol simulation | [Experiment 07](<Experiment 07 - ARP and RARP Protocol.py>) |
| 08 | TCP and UDP simulation using NS-2 | [Experiment 08](<Experiment 08 - TCP and UDP Simulation using NS2.tcl>) |
| 09 | Distance Vector routing using NS-2 | [Experiment 09](<Experiment 09 - Distance Vector Routing using NS2.tcl>) |
| 10 | Link State routing using NS-2 | [Experiment 10](<Experiment 10 - Link State Routing using NS2.tcl>) |
| 11 | Local DNS and IP address using Python | [Experiment 11](<Experiment 11 - Local DNS and IP Address.py>) |

## Requirements

- Python 3 for Python experiments.
- NS-2 and NAM for simulation experiments.
- Wireshark / Pktmon for packet capture and inspection.
- Windows Command Prompt / PowerShell or a Linux terminal for network commands.

## Running experiments

Clone this repository:

```bash
git clone https://github.com/hari-scsvmv/Computer-Network-Lab.git
cd Computer-Network-Lab
```

Run a Python experiment:

```bash
python "Experiment 02 - Machine Hostname and IP Address.py"
```

Run an NS-2 experiment:

```bash
ns "Experiment 08 - TCP and UDP Simulation using NS2.tcl"
```

For client-server experiments, start the server first and then run the client. Review each file and use only systems and networks you are authorized to test.

## Topics covered

- Network configuration, connectivity, DNS, route tracing, and packet analysis.
- Python socket programming, HTTP requests, TCP echo, chat, and file transfer.
- ARP/RARP address resolution.
- TCP/UDP traffic and Distance Vector / Link State routing simulations.

## Academic context

Computer Networks Laboratory coursework — Sri Chandrasekharendra Saraswathi Viswa Mahavidyalaya (SCSVMV University), B.Tech. CSE (AI & Data Science).
