# Architecture: 15-firebase-auth-starter

## Overview
A secure authentication boilerplate built with React 19 and Vite 6. Designed as a foundational "Security Protocol" unit, it leverages Firebase Auth for identity management and Framer Motion for high-fidelity state transitions between auth flows and dashboard views.

## Tech Stack
-   **Framework**: React 19
-   **Build Tool**: Vite 6
-   **Styling**: Tailwind CSS v4
-   **Backend**: Firebase 11 (Auth)
-   **Animations**: Framer Motion 12
-   **Icons**: Lucide React
-   **Routing**: React Router 7 (Pre-configured)

## Core Logic
-   **Auth State Management**: Centralized Firebase Auth observer pattern for real-time session tracking.
-   **Navigation Protocol**: Secure dashboard routing with animated view switching.
-   **Security Dashboard**: Modular components for session auditing, device tracking, and security scoring.
-   **Biometric Branding**: Technical UI elements simulating high-level encryption and biometric checks.

## Performance
-   Optimized for sub-second auth flow transitions via Vite 6.
-   Modular Firebase SDK imports to minimize final bundle size.
-   Hardware-accelerated glassmorphism effects for smooth 60fps interaction.
