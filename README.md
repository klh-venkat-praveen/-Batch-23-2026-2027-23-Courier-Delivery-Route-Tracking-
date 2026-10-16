# -Batch-23-2026-2027-23-Courier-Delivery-Route-Tracking-
# Courier Delivery Route & Tracking System

**Batch:** 23  
**Academic Year:** 2026–2027  
**Project No.:** 23

## 📌 Project Overview

The **Courier Delivery Route & Tracking System** is a Java-based project designed to calculate estimated courier delivery times, classify delivery statuses, organize courier records, and generate delivery reports.

The system accepts courier details such as courier ID, name, distance, speed, and extra handling time. It calculates the estimated delivery time and classifies each delivery as **Fast, Normal, or Delayed**.

## 🎯 Objectives

- Calculate estimated courier delivery time.
- Classify deliveries based on estimated time.
- Store and sort courier records.
- Calculate the total delivery distance.
- Identify and count delayed deliveries.
- Generate and save courier reports in a text file.
- Demonstrate Java programming concepts from all six course modules.

## ⚙️ Technologies Used

- **Programming Language:** Java
- **Input/Output:** Scanner and console output
- **Object-Oriented Programming:** Classes, objects, inheritance, and method overriding
- **Data Management:** Collections and sorting
- **File Handling:** Reading and writing text files
- **Data Processing:** Lambda expressions and Streams

## 🧮 Delivery Time Formula

Estimated delivery time is calculated using:

**Estimated Time = (Distance ÷ Speed) × 60 + Extra Handling Time**

The result is expressed in minutes.

### Delivery Status Rules

| Estimated Time | Status |
|---|---|
| 30 minutes or less | Fast |
| More than 30 and up to 120 minutes | Normal |
| More than 120 minutes | Delayed |

## 🚀 Key Features

1. Accepts courier delivery details.
2. Validates input data.
3. Calculates estimated delivery time.
4. Classifies delivery status automatically.
5. Sorts courier records by courier ID.
6. Calculates total delivery distance using recursion.
7. Counts delayed deliveries using Streams.
8. Saves the generated report to `courier_report.txt`.
9. Handles input and file-related errors.

## 📚 Java Concepts Demonstrated

- **Module 1:** Variables, data types, operators, and input/output.
- **Module 2:** Conditional statements and loops.
- **Module 3:** Methods, recursion, and arrays or collections where applicable.
- **Module 4:** Classes, objects, inheritance, overriding, and exception handling.
- **Module 5:** Strings, StringBuilder, and file handling.
- **Module 6:** Collections, Comparable, lambda expressions, Streams, and Collectors.

## 🧪 Sample Output

```text
CR101 Ravi     10 km   20 min   Fast
CR102 Praveen  20 km   35 min   Normal
CR103 Deepika 100 km  210 min   Delayed

Total Distance: 130 km
Delayed Deliveries: 1
```

*Sample output is illustrative of the project results.*

## ▶️ How
