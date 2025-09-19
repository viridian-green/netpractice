# NetPractice: Network Configuration Practice

## 📋 Table of Contents

- [About](#about)
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Level Structure](#level-structure)
- [Network Concepts](#network-concepts)
- [Submission Requirements](#submission-requirements)
- [Evaluation Process](#evaluation-process)
- [Tips & Strategies](#tips--strategies)

## About

**NetPractice** is a network configuration simulation project that teaches TCP/IP addressing fundamentals through hands-on practice. This web-based interface presents 10 progressively challenging networking problems that require proper IP addressing and subnet configuration to solve.

## Project Overview

NetPractice simulates real-world network troubleshooting scenarios where you must configure various network devices to establish proper connectivity. Each level presents a network diagram with misconfigured or incomplete settings that you need to correct.

### Key Learning Objectives
- Understanding TCP/IP addressing fundamentals
- Subnet mask calculation and CIDR notation
- Router and switch configuration
- Network segmentation and routing
- Troubleshooting network connectivity issues

## Getting Started

### Installation

1. **Download the netpractice folder** 
2. **Extract the files** to any directory of your choice
3. **Open `index.html`** in your web browser

### Interface Overview

The training interface provides:
- **Network diagram** showing devices and connections
- **Configuration goal** at the top of the window
- **Interactive fields** for entering IP addresses, subnet masks, and default gateways
- **Action buttons**: 
  - `[Check again]` - Validate your configuration
  - `[Get my config]` - Export your solution for submission
- **Log area** at the bottom for error messages and feedback

## Level Structure

The project consists of 10 levels with increasing complexity:

| Level | Focus Area | Typical Devices |
|-------|------------|-----------------|
| 1-2 | Basic addressing | Hosts, simple routers |
| 3-4 | Subnetting | Multiple subnets, routers |
| 5-6 | Complex routing | Multiple routers, static routes |
| 7-8 | Advanced subnetting | Variable length subnet masks |
| 9-10 | Enterprise scenarios | Complex network topologies |

### Example Level Goal
"Configure all devices so that:
- Host A can ping Host B
- Host C can access the internet
- All devices have valid IP addresses for their network"

## Network Concepts

### Essential Knowledge Areas

#### IP Addressing
- IPv4 address structure (32-bit, dotted-decimal notation)
- Network vs. host portions of addresses
- Private vs. public IP ranges
- Special addresses (network, broadcast)

#### Subnet Masks
- Purpose and function
- CIDR notation (e.g., /24, /26)
- Calculating network boundaries
- Determining valid host ranges

#### Default Gateways
- Router interface addresses
- Routing between networks
- Next-hop configuration

#### Device Types
- **Hosts**: End devices requiring IP configuration
- **Routers**: Devices connecting multiple networks
- **Switches**: Layer 2 devices (typically pre-configured)

### Exporting Configurations
1. **Enter your login** in the training interface before starting
2. **Complete each level** successfully
3. **Click `[Get my config]`** after solving each level
4. **Save the file** with the appropriate name (level1.txt, level2.txt, etc.)
5. **Place all files** in your Git repository

## Evaluation Process

### During Defense
- You will be asked to complete **3 random levels** within **15 minutes**
- No external tools allowed (basic calculator permitted)
- Evaluation may include minor modifications or additional challenges

### Success Criteria
- Correct IP addressing for all devices
- Proper subnet mask configuration
- Appropriate default gateway settings
- Functional connectivity as specified in the level goal
- No IP address conflicts

### Calculation Tools
- Practice binary to decimal conversion
- Learn to calculate network addresses quickly
- Understand how to determine broadcast addresses
- Master CIDR notation and its implications
