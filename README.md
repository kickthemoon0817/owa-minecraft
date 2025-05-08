# owa-minecraft

**owa-minecraft** is a recording tool for Minecraft, powered by Open-World-Agent.

## Overview

This project captures and processes minecraft data to log player actions and world events in real time.

## Plans

### 1. Raw Packet Recorder (In Progress)

- **Purpose:** Intercepts raw packets sent between the Minecraft server and client.  
- **Implementation:**  
  Uses [node-minecraft-protocol](https://github.com/PrismarineJS/node-minecraft-protocol) to hook into the protocol and emit structured events for analysis or storage.

### 2. MineScript Integration (In Progress)

- **Purpose:** Extends recording capabilities via a Forge/Fabric mod.  
- **Implementation:**  
  Integrates the [MineScript](https://github.com/maxuser0/minescript) mod on the target server to expose high-level game events (e.g., scripted sequences, custom block interactions).
