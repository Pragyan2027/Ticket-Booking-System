# 🚆 Ticket Booking System

A full-featured Ticket Booking System that enables users to search for trains, book tickets, manage their bookings, and more — all in one place! Built with a focus on user experience and modularity.

## ✨ Features

🔐 **User Authentication**  
- **Sign Up** – Create a secure account  
- **Login** – Authenticate existing users  

🎟️ **Ticket Management**  
- **Book Tickets** – Select train, class, and passengers to confirm bookings  
- **Cancel Booking** – Cancel your ticket anytime before departure  
- **Check Booked Tickets** – View your active bookings and details  

🚄 **Train Search**  
- **Look for Trains** – Search trains by source, destination, and date  
- **Fetch Train Details** – Get schedule, seat availability, and pricing info  

---

## 🛠️ Tech Stack Breakdown

### 💻 Backend

* **Language**: Java
* **Build Tool**: Gradle (`build.gradle` and `settings.gradle` present)
* **Architecture**: Likely modular with service and utility layers (`service/`, `util/`)
* **Testing**: JUnit (evident from `AppTest.java`)

### 🗃️ Database (Inferred)

* While no direct SQL file was found, it's likely:

  * Using **JPA/Hibernate** (common in Java apps with entities like `User.java`, `Train.java`, `Ticket.java`)
  * Could connect to **MySQL** or **H2** depending on config (need `application.properties` or DB connector to confirm)

### 📦 Project Structure

* `entities/` – POJO classes like `User`, `Train`, `Ticket`
* `service/` – Business logic for booking and train handling
* `util/` – Helper classes for operations like user management
* `App.java` – Main application entry point

### ⚙️ Build System

* Gradle Wrapper (`gradlew`, `gradle-wrapper.properties`)
* Configured with multi-project support (`app/` submodule)


