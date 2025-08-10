# Cypress API Testing Project – Restful-Booker API

## 📌 Project Overview
This project demonstrates automated API testing using **Cypress** with the **Restful-Booker API**.  
The goal was to perform a **health check** and functional tests for booking operations, validate API responses, and organize the test code.

---

## 🛠 Tools & Environment
- **Cypress** for automation testing
- **JavaScript** for writing tests
- **Restful-Booker API** for endpoint testing
- **MacOS** with VS Code as IDE

---

## 🧪 Tests Performed

### **1. Health Check Test**
- **Endpoint:** `GET /ping`
- **Purpose:** Verify API is operational
- **Result:** ✅ Passed (Status code `201 Created` returned correctly)

### **2. Create Booking**
- **Endpoint:** `POST /booking`
- **Payload:** JSON body with booking details
- **Result:** ✅ Passed (Booking successfully created, `200 OK` status)

### **3. Get Booking**
- **Endpoint:** `GET /booking/{id}`
- **Purpose:** Fetch details of an existing booking
- **Result:** ✅ Passed (Correct booking details returned)

### **4. Update Booking**
- **Endpoint:** `PUT /booking/{id}`
- **Purpose:** Modify booking details
- **Result:** ✅ Passed (Booking updated successfully)

### **5. Delete Booking**
- **Endpoint:** `DELETE /booking/{id}`
- **Purpose:** Remove a booking
- **Result:** ✅ Passed (Booking deleted successfully)

---

## 🎥 Project Demonstration
📌 **Screen Recording of All Tests**: [Click Here to View] https://drive.google.com/file/d/1ifrEzj2wraYle65LoIx0T5sbFldobAKB/view?usp=sharing

---

## 📂 Project Structure
