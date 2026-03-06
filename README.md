# Swiss System Tournament

Swiss System Tournament is a web application for creating and managing tournaments that use the Swiss pairing format. It helps organizers enter players, generate matchups across multiple rounds, record match outcomes, and keep track of standings during the tournament.

The project was built as a frontend application using Quasar, Vue 3, and TypeScript, with additional tools for state management, routing, persistence, and communication.

## Features

- Create and manage a Swiss-system tournament
- Add and edit players
- Generate matchups for tournament rounds
- Record match results
- Track player standings and tournament progress
- Navigate between rounds
- Maintain a tournament schedule view
- Share tournament-related information by email
- Store and load tournament data

## Tech Stack

### Frontend
- Quasar Framework
- Vue 3
- TypeScript
- JavaScript
- SCSS

### Libraries and Tools
- Pinia for state management
- Vue Router for navigation
- Firebase for data storage/integration
- EmailJS for sending emails
- vuedraggable for drag-and-drop interactions
- Font Awesome icons

## Project Structure

```text
Swiss-system-tournament/
├── quasar-project/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── boot/
│   │   ├── components/
│   │   ├── css/
│   │   ├── enums/
│   │   ├── firebase/
│   │   ├── models/
│   │   ├── pages/
│   │   ├── router/
│   │   └── App.vue
│   ├── package.json
│   ├── quasar.config.js
│   └── tsconfig.json
└── README.md
