# 🎟️ Movie Ticket Booking System

A **console-based movie ticket booking system** built using **C++**, demonstrating clean **object-oriented design**, **multithreading**, and **core software design patterns**.

---

## 🚀 Features

- 🎬 Manage movies, theatres, screens, and show timings
- 🪑 Book seats with thread-safe locking to prevent double-booking
- 🔒 In-memory seat lock mechanism with configurable timeouts
- 💳 Modular payment system using the **Strategy Pattern**
- 🧱 Clean MVC-style architecture (Model, Service, Controller)

---

## 🧠 Design Highlights

| Pattern Used      | Purpose                                        |
|-------------------|------------------------------------------------|
| **Strategy**       | Dynamic payment processing methods             |
| **Service Layer**  | Modular business logic (booking, show, seat)   |
| **In-Memory Lock** | Prevent race conditions during booking         |
| **Controller Layer** | Acts as interface between user and services |

---

## 📦 Folder Structure

```
MovieBookingSystem/
├── src/
│   ├── model/         # Movie, Show, Seat, User, Booking, etc.
│   ├── service/       # Business logic (BookingService, etc.)
│   ├── controller/    # Interface layer for interaction
│   ├── lock/          # Seat lock handling and validation
│   └── main.cpp       # Entry point to simulate bookings
```

---

## 🧪 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/MovieBookingSystem.git
   cd MovieBookingSystem
   ```

2. Compile and Run  
   ```bash
   g++ -std=c++17 src/main.cpp -o booking
   ./booking
   ```

3. Or use any C++ IDE (e.g., CLion, Code::Blocks, VSCode)

---

## ⚙️ Tech Stack

- **Java**
- **Collection Framework**
- **Multithreading (thread, mutex)**
  

---

## 🧩 Future Extensions

- ✅ Add file/database persistence (SQLite, JSON)
- ✅ Web or GUI frontend
- ✅ Email confirmations and session management
- ✅ RESTful API layer

---

## 🤝 Contribution

Pull requests and feedback are welcome!  
If you'd like to extend it to GUI or web, feel free to fork and build on it.

---

## 📄 License

MIT License

---

### 💡 Built for learning, scalability, and clean system design.
