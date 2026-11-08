# ⚡ Smart EV Charging Station Management System

## 📌 Project Description
The Smart EV Charging Station Management System is a C++-based application designed to manage electric vehicle charging stations efficiently. It allows users to register vehicles, manage charging stations, prioritize vehicles based on battery levels, calculate charging costs, and maintain billing history.

The system automatically assigns available charging stations to vehicles with lower battery percentages, helping reduce waiting time and improve station utilization.

## 🎯 Objectives
- Manage multiple EV charging stations.
- Register electric vehicles and their details.
- Prioritize vehicles with low battery levels.
- Automatically allocate available charging stations.
- Calculate charging energy and billing amounts.
- Maintain charging and billing history.

## 🛠️ Technologies Used
- **Programming Language:** C++
- **Data Structures:** Structures, Vectors, Arrays
- **Algorithms:** Sorting and Linear Search
- **Concepts:** Priority Scheduling, Queue Management
- **Compiler:** GCC / MinGW
- **IDE:** Visual Studio Code / Code::Blocks

## 💻 System Requirements

### Hardware Requirements
- Computer or Laptop
- Minimum 4 GB RAM
- Keyboard and Monitor

### Software Requirements
- Windows or Linux
- C++ Compiler
- VS Code / Code::Blocks

## ✨ Features
1. **Vehicle Registration:** Register vehicles with ID, owner name, battery level, and battery capacity.
2. **Station Management:** Display three charging stations and their availability.
3. **Vehicle Management:** View registered vehicle details and charging status.
4. **Waiting Queue:** Manage vehicles waiting for charging.
5. **Priority Allocation:** Give priority to vehicles with lower battery percentages.
6. **Charging and Billing:** Calculate required energy and generate charging bills.
7. **Charging History:** Maintain previous charging and billing records.

## ⚙️ How It Works
1. The user registers an electric vehicle.
2. The system validates the vehicle details.
3. The vehicle is added to the waiting queue.
4. Vehicles are sorted according to battery percentage.
5. Available charging stations are automatically allocated.
6. The user completes charging through the menu.
7. The system calculates energy consumption and the total bill.
8. The station becomes available for the next vehicle.
9. Charging and billing details are stored in history.

## 🧮 Algorithms Used
- **Sorting:** Arranges vehicles based on battery percentage.
- **Linear Search:** Finds vehicle details using Vehicle ID.
- **Priority Scheduling:** Gives higher priority to low-battery vehicles.
- **Queue Management:** Maintains waiting vehicles.
- **Greedy Allocation:** Assigns vehicles to available stations.

## 📐 Mathematical Formulas

**Required Charging Energy:**

Energy = Battery Capacity × (100 - Current Battery %) / 100

**Charging Bill:**

Total Bill = Energy Consumed × Charging Rate

**Charging Rate:** ₹10 per kWh.

### Example
- Battery Capacity: 60 kWh
- Current Battery: 20%
- Energy Required: 48 kWh
- Charging Rate: ₹10/kWh
- Total Bill: ₹480

## 📋 Main Menu
1. Register Vehicle & Request Charging
2. View Charging Stations
3. View Registered Vehicles
4. View Waiting Queue
5. Complete Charging & Generate Bill
6. View Charging & Billing History
7. Exit

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Save the source code as `main.cpp`.
4. Compile the program:

```bash
g++ main.cpp -o ev_charging
```

5. Run the program:

```bash
./ev_charging
```

For Windows:

```bash
ev_charging.exe
```

## ✅ Advantages
- Reduces vehicle waiting time.
- Provides automatic station allocation.
- Prioritizes low-battery vehicles.
- Simplifies charging cost calculations.
- Maintains charging and billing history.
- Reduces manual management.

## 🌍 Applications
- Public EV charging stations.
- Shopping malls.
- College and university parking areas.
- Office parking facilities.
- Commercial EV charging centers.

## 🔮 Future Enhancements
- Real-time battery monitoring.
- Web and mobile application integration.
- Database connectivity.
- Online payment integration.
- Solar-powered charging support.
- Live station availability notifications.
- Support for multiple charging stations.

## ⚠️ Limitations
- Currently supports only three charging stations.
- Charging is simulated, not performed using physical hardware.
- No real-time battery monitoring.
- No permanent database storage.
- No online payment facility.

## 🏁 Conclusion
The Smart EV Charging Station Management System demonstrates how C++ programming, data structures, sorting, searching, and priority scheduling can be used to manage electric vehicle charging stations efficiently. It provides automatic vehicle allocation, charging cost calculation, and billing history management.

## 👨‍💻 Project Category
**Domain:** Electric Vehicle Management  
**Project Type:** C++ Mini Project  
**Topic:** Smart EV Charging Station Management System
