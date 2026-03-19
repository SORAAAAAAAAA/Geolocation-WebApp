# JLabs Assessment - Frontend

## Overview

This repository contains the Next.js frontend application for the JLabs Assessment. It provides a user interface for geolocation tracking and mapping.

## Technologies Used

- Next.js (React Framework)
- TypeScript
- Tailwind CSS
- Leaflet / React-Leaflet (Mapping)
- pnpm (Package Manager)

## Prerequisites

Before running the application, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [pnpm](https://pnpm.io/installation) (Package manager)

## Getting Started

Follow these steps to set up and run the frontend application locally.

### 1. Environment Configuration

Create the necessary environment variable file by copying the provided example and filling in the appropriate values.

```bash
cp .env.example .env
```

### 2. Install Dependencies

Install the frontend dependencies:

```bash
pnpm install
```

### 3. Start the Development Server

Start the Next.js development server:

```bash
pnpm run dev
```

Alternatively, if you wish to run a production build:

```bash
pnpm run build
pnpm run start
```

### 4. Access the Application

Once the development server is running, you can access the application in your web browser at `http://localhost:3000` (unless the port is occupied).
