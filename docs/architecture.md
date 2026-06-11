# Architecture

## Components

### Firmware Layer
STM32-based firmware monitoring IPS fault signals via optocoupler isolation.

### Communication Layer
Transmits real-time sensor data over WebSocket to the dashboard.

### Digital Twin Dashboard
Browser-based visualization reflecting live IPS system state.

## Data Flow

IPS Hardware → STM32 Firmware → WebSocket Bridge → Dashboard
