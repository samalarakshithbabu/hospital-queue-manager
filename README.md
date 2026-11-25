# Hospital Queue Manager

A simple hospital queue management web application to register patients, prioritize them based on emergency level, and manage check-ins and check-outs.

---

## Problem Statement

Hospitals need a lightweight system to manage patient queues with priority-based ordering and checkout tracking.

## Objectives

- Register patients with name, emergency level, and symptoms
- Display current patient queue in a table
- Support priority levels: Critical, Moderate, Normal
- Allow checkout/removal of patients after treatment

## Key Features

- **Patient Check-In** — name, emergency level, and symptoms
- **Queue Display** — table view of current patients
- **Priority Levels** — Critical, Moderate, Normal
- **Checkout Management** — remove patients after treatment
- **Modular JavaScript** — reusable counter module

## Technologies Used

| Component | Technology |
|-----------|-----------|
| Frontend | HTML, CSS, JavaScript (Vanilla) |
| Backend | Assumes API at `http://localhost:3000` |
| Modules | Modular JS (counter.js) |

## Project Structure

```
hospital-queue-manager/
├── index.html       # Main HTML page
├── style.css        # Styling
├── main.js          # Core logic for form and queue handling
├── counter.js       # Reusable counter module
├── server.js        # Backend server
├── package.json     # Node.js dependencies
└── README.md
```

## Installation and Setup

### Prerequisites
- Node.js 14+
- npm

### Setup
```bash
npm install
node server.js
```

Application expects backend API at `http://localhost:3000`.

## Limitations

- Assumes external backend API
- No persistent database (in-memory or API-dependent)
- No user authentication

## Author and Contact Information

**SAMALA RAKSHITH BABU**

- Email: samalarakshithbabu7@gmail.com
- LinkedIn: https://www.linkedin.com/in/samala-rakshith-babu-9374ab281/
- GitHub: https://github.com/samalarakshithbabu

## License

MIT License (badge-confirmed; file path not verified).