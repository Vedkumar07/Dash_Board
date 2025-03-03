# Interactive Workflow Builder

## Overview
The **Interactive Workflow Builder** is a dynamic, drag-and-drop tool for designing task automation flows. It enables users to create, edit, and visualize workflows in real-time, using an intuitive node-based interface. 

## Features

### 🔹 Node-Based UI
- Add, move, and connect nodes to build workflows.
- Each node represents an action (e.g., Fetch Data, Transform, Send Email).
- Drag-and-drop functionality for smooth interaction.

### 🔹 Real-Time Execution
- WebSockets enable live updates and real-time workflow changes.
- Dynamic processing of input data.

### 🔹 JSON Data Handling
- Each node takes JSON input and produces JSON output.
- Example JSON representation:
  ```json
  {
    "id": "1",
    "type": "Fetch Data",
    "output": {
      "users": [
        {"id": "101", "name": "Alice", "description": "Admin"},
        {"id": "102", "name": "Bob", "description": "Editor"}
      ]
    }
  }
### 🔧 Tech Stack
-Frontend: React.js / Next.js (UI Development)
-Graph Visualization: D3.js / React Flow
-Real-Time Processing: WebSockets
-Data Handling: JSON processing & visualization

###  Run the App

-npm run dev
-node server.js
