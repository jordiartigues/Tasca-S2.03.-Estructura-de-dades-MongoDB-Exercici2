# MongoDB Data Modeling – Optical Store

**Description:** Design of a NoSQL data model for a fictional optical store. The project focuses on managing clients, purchases, glasses, employees and suppliers using MongoDB document-oriented modeling, embedded documents and references with ObjectId.

## 🛠 Technologies

* **MongoDB Compass:** Database and collection management.
* **Git / GitHub:** Version control and project hosting.

## 📂 Project Structure

* **`cul_dampolla_ex2.clients.json`:** Client information, contact details, and referral tracking (`recommendedBy`).
* **`cul_dampolla_ex2.glasses.json`:** Glasses catalog, prices, embedded supplier information, and a summary sales array for fast rendering.
* **`cul_dampolla_ex2.employees.json`:** Optical store employee information.
* **`cul_dampolla_ex2.sales.json`:** Global transaction history linking glasses, clients, and employees with precise prescription details.

## 🧠 What I Learned

* Designing NoSQL databases using MongoDB.
* Working with embedded documents and arrays.
* Establishing relationships between collections using ObjectId references.
* Choosing between embedded documents and references depending on data structure and access needs.
* Organizing data to support efficient read operations.

## 🚀 Installation & Usage

1. Clone the repository.
2. Open MongoDB Compass and connect to your local MongoDB instance.
3. Create a database named `cul_dampolla`.
4. Import the provided JSON files into their corresponding collections (`cul_dampolla_ex2.clients`, `cul_dampolla_ex2.glasses`, `cul_dampolla_ex2.employees`, `cul_dampolla_ex2.sales`).
5. Explore the documents and relationships using MongoDB Compass.

## 📸 Demo

The project is a local MongoDB database model. There is no online demo available. The database structure and documents can be explored using MongoDB Compass.

## 👨‍💻 Author

Jordi
