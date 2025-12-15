# Real-Time Financial Data Feed Processor (JPMorgan Chase Job Simulation)

## 📌 Project Overview
This project is a real-time stock price monitoring system developed as part of the **JPMorgan Chase Software Engineering Job Simulation**. It is designed to consume, process, and visualize high-frequency financial data, simulating a trading floor environment where latency and accuracy are critical.

The system features a **Spring Boot** backend that interfaces with a data feed, processes stock updates, and serves them to a frontend dashboard for live visualization.

## 🚀 Key Features
* **Real-Time Data Streaming:** Processes live stock market data feeds with minimal latency.
* **Backend Engineering:** Built RESTful APIs using **Java (Spring Boot)** to handle data requests and serve trade information.
* **Data Persistence:** Implemented **Spring Data JPA** to manage and persist transaction records efficiently.
* **Data Visualization:** Integrated with a frontend (React-based) to render "Graph" visualizations of stock price fluctuations, identifying convergence points for trading alerts.
* **Scalability Consideration:** Designed the architecture to handle continuous data streams, simulating high-throughput financial systems.

## 🛠️ Tech Stack
* **Language:** Java (Core & Advanced)
* **Framework:** Spring Boot, Spring Data JPA
* **Build Tool:** Maven/Gradle
* **Architecture:** RESTful API, MVC Pattern
* **Additional Tools:** Git, JUnit (for testing)

## ⚙️ How It Works (System Design)
1.  **Data Ingestion:** The system connects to a server-side feed providing continuous stock price updates.
2.  **Processing Logic:**
    * Calculates the ratio between two stock prices (e.g., ABC and DEF).
    * Determines if the ratio crosses a specific threshold (upper/lower bounds).
    * Triggers an "Alert" when a trading opportunity is identified.
3.  **API Response:** The processed data (timestamp, ratio, trigger_alert) is sent to the client via REST endpoints.

## 🔧 Setup & Installation
To run this project locally:

1. **Clone the repository:**
   ```bash
git clone [https://github.com/subashchand/SoftwareEngineering_JobSimulation_BackEnd_JPMorgan.git](https://github.com/subashchand/SoftwareEngineering_JobSimulation_BackEnd_JPMorgan.git)
