# 🏨 Hotel Reservation System

A Java console application to manage hotel reservations. The program allows you to register a reservation with room number, check-in date, and check-out date, calculates the stay duration in days, and supports updating the dates as long as business rules are respected.

## ✨ Features

- Create a reservation (room + dates)
- Automatic calculation of stay duration (in nights)
- Update reservation dates
- Strict validation rules:
  - Check-out date **must be after** check-in date
  - Changes are only allowed for **future dates** (relative to the current date)
- Exception handling for invalid inputs (date format errors, broken rules, etc.)

## 🛠️ Technologies Used

- Java 17 (or higher)
- `java.time` API (`LocalDate`, `DateTimeFormatter`, `ChronoUnit`)
- `Scanner` for console input

## 📐 Project Structure
