# EMPower

## Overview

**EMPower** is an EV Charging Management Platform  developed as an academic full-stack platform for EV charging service management. It allows electric vehicle users to **discover, browse, navigate to, and reserve charging points** through a web and mobile-friendly 
interface. In parallel, it provides provider-side management and monitoring capabilities through a **REST API** and a 
**Command Line Interface (CLI)**.

> This repository is a public showcase of the EMPower academic project.  
> Source code is intentionally not included, as the project remains under active academic development in a private team repository.

## Features

### User Features
- Access the platform via a responsive web-based interface designed for desktop and mobile usage
- Browse EV charging points through an interactive map
- Filter charging points based on availability, status, plug type
- View detailed information for a selected charging point
- Get navigation directions to a selected charging point via external map services
- Reserve an available charger and view the reservation status in real time

### Provider Features
- Manage EV charging points and their operational status
- Add new charging points to the system
- Monitor system health and overall charging point activity
- Access provider-side functionality through a RESTful API and a Command Line Interface (CLI)

## Architecture & Technology Stack

EMPower follows a modular architecture consisting of a frontend, a backend exposing a RESTful API, a database, and a provider-side CLI. All components are containerized for consistent deployment.

- **Frontend**: Responsive web application for desktop and mobile devices.  
  *Stack:* Next.js (React, TypeScript), Tailwind CSS, Radix UI / shadcn, MapLibre GL.

- **Backend & REST API**: Implements core business logic and exposes REST endpoints consumed by the frontend and CLI.  
  *Stack:* Python, FastAPI, SQLAlchemy, Pydantic, Uvicorn.

- **Database**: Persistent storage for charging points, reservations, status history, and sessions.  
  *Stack:* PostgreSQL.

- **Command Line Interface (CLI)**: Provider-side tool for administrative and monitoring operations via the REST API.  
  *Stack:* Python, Typer, Requests.

- **Deployment**: Containerized runtime environment.  
  *Stack:* Docker, Docker Compose.

## Preview

<img width="960" height="448" alt="image" src="https://github.com/user-attachments/assets/548949ba-a3f0-4455-9dc0-2dd3dc4df0d6" />
<img width="960" height="448" alt="image" src="https://github.com/user-attachments/assets/feffc22f-495d-4d1d-8c01-b5fb3d099cab" />
<img width="960" height="449" alt="image" src="https://github.com/user-attachments/assets/7509cdb0-8ab1-46bf-a5b4-981cbd09ea46" />
<img width="960" height="448" alt="image" src="https://github.com/user-attachments/assets/9f22b4aa-7dd1-4e7c-8f9c-8e90ccc703ea" />

## Academic Context

Developed as a team project for the NTUA Software Engineering course, Oct 2025 – Feb 2026.
