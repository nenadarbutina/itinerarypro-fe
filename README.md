# ItineraryPro-FE (Angular Frontend Application)

## 🚀 Project Description

**ItineraryPro-FE** is the official Single Page Application (SPA) for the ItineraryPro platform. Built with **Angular**, it provides a dynamic, responsive user interface for both tourist agency agents (Agent Dashboard) and end-customers (Online Booking Engine).

## 💡 Key Features

* **Agent Dashboard:** Centralized view for managing bookings, inventory, and clients.
* **Online Booking Engine:** Complex search, filtering, and reservation workflow for customers.
* **Role-Based UI:** Dynamic content rendering based on the logged-in user's role (Agent vs. Customer).

## 🛠️ Technology Stack

* **Framework:** Angular (latest version)
* **Language:** TypeScript
* **State Management:** NgRx (or feature-specific Angular Services)
* **Styling:** SCSS, potentially paired with a component library (e.g., Angular Material)
* **HTTP Client:** Angular HttpClient to communicate with the **ItineraryPro-BE** API Gateway.

## 💻 Getting Started (Setup)

### Prerequisites

* Node.js (LTS version)
* npm (comes with Node.js)
* Angular CLI

### 1. Installation

1.  Clone this repository:
    `git clone [Your GitHub URL]/ItineraryPro-FE.git`
2.  Navigate into the project directory:
    `cd ItineraryPro-FE`
3.  Install dependencies:
    `npm install`

### 2. Configuration

Ensure the `environment.ts` file points to the correct URL of the **ItineraryPro-BE API Gateway** (default: `http://localhost:8080`).

```typescript
// Example: src/environments/environment.ts
export const environment = {
  production: false,
  apiBaseUrl: 'http://localhost:8080/api/v1', 
};
