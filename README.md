# FleetCam: Advanced Fleet Management and Surveillance System

**FleetCam** is a comprehensive fleet management solution built on the robust [Traccar](https://github.com/traccar/traccar) open-source platform. Designed to integrate real-time video surveillance with GPS-based vehicle tracking, FleetCam empowers administrators with tools for effective fleet monitoring and operational control.

---

## Features

### 🌐 **Real-Time Video Streaming**
- **Mobile Integration:** A WebRTC-powered mobile application provides real-time video streaming from vehicles.
- **Administrator Access:** Administrators can view live footage directly from the Traccar web interface, ensuring seamless monitoring.

### 📊 **Vehicle Tracking and Historical Data**
- Leverages Traccar's reliable GPS tracking system for real-time location updates.
- Provides access to historical tracking data and recorded video footage for thorough incident reviews.

### 📋 **CRM Module**
- Integrated customer relationship management (CRM) capabilities for streamlined fleet and customer operations.
- Manage driver profiles, schedules, and customer interactions.

### 🤖 **Telegram Bot Integration**
- **Notifications:** Receive real-time alerts and updates about fleet activity.
- **Quick Access:** View GPS data, video footage, and vehicle status directly from Telegram.

---

## Technical Overview

### 🚀 **Technology Stack**
- **Backend:** Traccar platform with extended functionality.
- **Frontend:** WebRTC-based mobile app and Traccar web interface for video streaming and control.
- **Messaging:** Telegram bot API for administrator notifications and interactions.
- **Database:** SQLite for persistent mobile data storage.

### 📱 **Mobile Application**
- Built with **React Native**.
- Runs as a **background service** to avoid distracting drivers.
- Optimized for real-time streaming and local data uploads.

### 🔌 **Integration**
- Fully compatible with Traccar's API, ensuring smooth data exchange.
- Supports cloud and decentralized storage options for video data.

---

## Use Cases

- **Fleet Management:** Monitor and manage large fleets in real-time.
- **Driver Accountability:** Track driver behavior with live video and location data.
- **Incident Investigation:** Use historical data and footage for resolving disputes or reviewing incidents.
