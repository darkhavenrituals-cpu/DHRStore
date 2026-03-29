# Dark Haven Rituals (DHR) Sovereign System

![DHR Logo](public/Logo.png)

## Overview
Dark Haven Rituals (DHR) is a comprehensive full-stack ecosystem designed for the sovereign individual. It combines ancient ritual wisdom with modern cognitive science to provide high-performance neural tools and infrastructure.

This repository contains the **Sovereign Console v2.4.0**, a centralized management interface for DHR operations, alongside the consumer-facing **Ritual Store** and **Visual Archives**.

## Key Features

### 1. Ritual Store
- **Neural Blends:** Access to foundational (Genesis), peak-performance (Ascension), and experimental-grade (Singularity) nootropic formulations.
- **AI Image Generation:** Admin-only capability to generate unique product visuals using Gemini AI based on formulation descriptions.
- **Secure Checkout:** Integrated order management system.

### 2. Sovereign Console (Executive Interface)
- **AI Strategic Command:** Specialized AI assistants tailored for the **CEO (Przemysław)** and **COO (Luljeta)**, providing strategic advice based on personality traits and company documentation.
- **Neural Market Feed:** A live, 15-minute updating intelligence feed pulling real-time global news related to coffee futures, organic ingredients, and logistics using Gemini AI with Google Search grounding.
- **Departmental Oversight:** Visual tracking of organizational growth across Finance, R&D, Sales, PR, Legal, Operations, CX, Data, and HR.
- **Store Management:** Real-time monitoring of orders, inventory, and business metrics.

### 3. Visual Archives (Gallery)
- **Artifact Management:** Secure storage and display of DHR media.
- **Advanced Uploads:** Support for drag-and-drop and manual file browsing, with metadata persistence in Firestore.

### 4. The Science & Campaign
- **Educational Infrastructure:** Deep dives into the bio-chemical and psychological foundations of DHR rituals.
- **Investor Deck:** Integrated presentation module for strategic growth and funding rounds.

## Tech Stack

- **Frontend:** React 18+, TypeScript, Vite, Tailwind CSS.
- **Animations:** Framer Motion (`motion/react`).
- **Icons:** Lucide React.
- **Backend:** Node.js (Express) with custom API routes for file handling and history logging.
- **Database:** Firebase Firestore (Real-time data synchronization).
- **Authentication:** Firebase Auth (Google OAuth).
- **AI Engine:** Google Generative AI (Gemini 3.1 Pro/Flash) with Search Grounding.
- **Document Editing:** React Quill.
- **Data Visualization:** Recharts.

## Setup & Installation

### Prerequisites
- Node.js (v18+)
- Firebase Project (Firestore & Auth enabled)
- Google Gemini API Key

### Environment Variables
Create a `.env` file in the root directory:
```env
GEMINI_API_KEY=your_gemini_api_key
GOOGLE_CLIENT_ID=your_google_oauth_client_id
GOOGLE_CLIENT_SECRET=your_google_oauth_client_secret
APP_URL=your_application_url
