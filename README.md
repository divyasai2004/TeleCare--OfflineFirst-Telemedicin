# TelCare — Offline First Telemedicine Platform

TelCare is a modern **offline-first telemedicine platform** designed to improve healthcare accessibility in rural and low-bandwidth regions. The platform enables users to perform AI-powered symptom analysis, consult doctors remotely, manage digital health records, analyze lab reports, and locate medicines or pharmacies—all while maintaining reliability under unstable internet conditions.

TelCare focuses on making healthcare more accessible, intelligent, and resilient through AI-powered assistance and offline-capable system design.

---

## Overview

Healthcare accessibility remains a major challenge in many regions due to unreliable internet connectivity, limited medical infrastructure, and delayed access to doctors. TelCare addresses these challenges by providing essential telemedicine services that continue functioning even when connectivity is poor or intermittent.

The platform combines artificial intelligence, real-time communication, secure health data storage, and offline fallback mechanisms to deliver a seamless healthcare experience.

---

## Features

### AI Symptom Checker

* AI-powered symptom analysis using Groq (Llama 3.3)
* Offline rule-based fallback for low-connectivity scenarios
* Severity-based risk classification
* Multilingual assistance (English and Hindi)

### Remote Consultation

* Patient-to-doctor communication
* Real-time messaging for faster consultations
* Improved healthcare access for remote users

### Digital Health Records

Secure storage and management of:

* Medical history
* Prescriptions
* Diagnostic reports
* Treatment records

### MediScan AI

* AI-assisted medical report interpretation
* Lab report analysis
* PDF report export

### Medicine & Pharmacy Finder

* Search medicines
* Locate nearby pharmacies
* Voice-assisted search for accessibility

### Voice Assistance

* Speech-to-text input using Whisper
* Helpful for users with limited typing ability

### Offline-First Architecture

* Supports unreliable or low-bandwidth networks
* Core functionality remains usable offline
* Automatic fallback logic for critical workflows

---

## Tech Stack

### Frontend

* React
* Next.js
* TypeScript
* Tailwind CSS

### Backend

* Node.js
* Next.js API Routes

### Database / Backend Services

* Supabase

### AI Services

* Groq API (Llama 3.3)
* Whisper API

### Development Tools

* Git
* GitHub
* CI/CD

---

## Architecture

```text
Client (React / Next.js)
        ↓
API Layer
        ↓
Business Logic
 ├── AI Symptom Engine
 ├── Offline Rule Engine
 ├── MediScan AI
 └── Pharmacy Finder
        ↓
Supabase Database
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/divyasai2004/TeleCare--OfflineFirst-Telemedicin.git
```

### Navigate to Project Directory

```bash
cd TeleCare--OfflineFirst-Telemedicin
```

### Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
GROQ_API_KEY=your_groq_api_key
```

---

## Running Locally

Start development server:

```bash
npm run dev
```

Open the application in your browser:

```text
http://localhost:3000
```

---

## Production Build

Build the application:

```bash
npm run build
```

Start production server:

```bash
npm start
```
