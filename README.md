# Work/Schedule Display

## Project Overview

The Work/Schedule Display is a smart desktop productivity device inspired by Spotify's clean and simple "Now Playing" interface. Instead of displaying music information, it displays assignments, schedules, reminders, tasks, and upcoming events.

I created this project because I often struggle to keep track of school assignments, engineering projects, and daily responsibilities. I wanted a dedicated device that could sit on my desk and show exactly what I need to work on without opening my phone or computer.

The project uses an ESP32-S3 microcontroller, a 2-inch TFT display, and physical navigation buttons to create a compact productivity dashboard. Future versions may include WiFi synchronization, voice commands, and integration with online task-management platforms.

---

# Final Assembly

## Front View

![Front View](images/front-view.jpg)

The enclosure is constructed from foam board and painted black to create a clean desktop appearance. The display mounts on the front panel and the navigation buttons are positioned below the screen.

## Internal Electronics

![Internal Electronics](images/internal-view.jpg)

The interior contains:

- ESP32-S3 Development Board
- Breadboard
- Navigation Buttons
- Wiring Harness
- Display Connections

The breadboard simplifies wiring and allows components to be modified during development.

---

# Project Concept

![Project Concept](Screenshot%202026-06-03%20165051.png)

The original concept was to create a productivity-focused display with a Spotify-inspired user interface that presents daily assignments, reminders, and schedules in a clean and readable format.

---

# Features

- Daily task display
- Schedule tracking
- Assignment reminders
- Task completion system
- WiFi connectivity
- Physical navigation buttons
- Spotify-inspired interface

---

# Hardware

| Component | Purpose |
|------------|------------|
| ESP32-S3 | Main microcontroller |
| 2-inch TFT Display | User interface |
| Push Buttons | Navigation controls |
| Breadboard | Rapid prototyping |
| Jumper Wires | Electrical connections |
| Foam Board Enclosure | Physical housing |

---

# CAD Files

The enclosure was designed to hold:

- ESP32-S3
- TFT Display
- Breadboard
- Wiring
- Navigation Buttons

Included CAD files:

- WorkScheduleDisplay.step
- Magnificent Snicket (1).stl

Original editable design:

https://www.tinkercad.com/things/3W4l3RVqBqP/edit

---

# Firmware

Firmware is located in:

```
/firmware/main.ino
```

The firmware controls:

- Display rendering
- Menu navigation
- Button inputs
- Task display system

---

# Wiring Diagram

Wiring documentation is located in:

```
docs/wiring-diagram.md
```

The project uses:

- ESP32-S3
- Breadboard
- Three navigation buttons
- TFT display connections

---

# Build Process

### Step 1: CAD Design

The enclosure was designed in CAD and exported as STL and STEP files.

### Step 2: Enclosure Construction

The enclosure was constructed from foam board and painted black.

### Step 3: Electronics Installation

The ESP32-S3, breadboard, display, and buttons were mounted inside the enclosure.

### Step 4: Firmware Development

Firmware was developed using Arduino IDE and uploaded to the ESP32-S3.

### Step 5: Testing

Buttons, display output, and navigation logic were tested to verify proper operation.

---

# Goals

The goal of this project is to create a dedicated productivity display that helps students stay organized and focused throughout the day.

---

# Bill of Materials (BOM)

| Quantity | Part | Link |
|-----------|-----------|-----------|
| 1 | LAFVIN ESP32S3 AI Chatbot Kit | https://www.amazon.com/gp/product/B0FHP8DN4S |
| 1 | Foam Board | https://www.homedepot.com/p/Owens-Corning-FOAMULAR-NGX-Insulating-Sheathing-0-5-in-x-4-ft-x-8-ft-SE-R-3-XPS-Rigid-Foam-Board-Insulation-13NGX/315193939 |
| 3 | Push Buttons | Included in Kit |
| 1 | TFT200C Display | Included in Kit |
| 1 | Breadboard | Included in Kit |
| Several | Jumper Wires | Included in Kit |

---

# Repository Structure

```
WorkScheduleDisplay/
│
├── firmware/
│   └── main.ino
│
├── docs/
│   └── wiring-diagram.md
│
├── images/
│
├── WorkScheduleDisplay.step
├── Magnificent Snicket (1).stl
├── BOM.csv
├── README.md
└── LICENSE
```
