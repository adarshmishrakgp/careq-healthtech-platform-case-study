# Careq-healthtech-platform-case-study
End-to-end healthtech platform built from scratch for appointment booking, live queue management, doctor operations, payments, prescriptions, and real-time coordination.

# CareQ — Real-Time HealthTech Platform

CareQ is a full-stack healthcare platform built to reduce patient waiting time and improve appointment and queue management across patients, doctors, and administrators.

The product was developed as a connected ecosystem consisting of a patient-facing mobile application, doctor-side web application, backend services, real-time queue workflows, payments, prescriptions, and administrative controls.
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/762518cf-0d0c-4e2b-8959-d0abde701742" />
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/095d2274-26da-4f01-9fb6-16f964cb7a04" />
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/e9ace028-f4ee-4367-9be5-ef142a32b879" />
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/f4ad2a0f-b5c8-43e0-96d4-b205101c40ed" />


## Product Overview

CareQ helps patients discover specialists, book appointments, join live queues, complete payments, and access prescriptions through a simple mobile experience.

Doctors and clinic teams can manage walk-ins, scheduled appointments, active queues, patient flow, and operational analytics from a dedicated web application.

Real-time synchronization keeps patients and doctors updated as queue positions, appointment status, and availability change.

## My Role

**Co-Founder and Full-Stack Developer**

My responsibilities included:

- Contributing to product planning and feature prioritization
- Developing the React Native patient application
- Building doctor-side workflows and management interfaces
- Integrating mobile and web applications with backend APIs
- Implementing real-time queue synchronization using WebSockets
- Supporting authentication, payments, appointments, and prescription workflows
- Contributing to backend development using NestJS
- Designing a modular and scalable product architecture
- Testing, debugging, and improving application usability

## Platforms Delivered

### Patient Mobile Application

The mobile application allows patients to:

- Register and manage their profile
- Discover doctors and specialists
- View available appointment slots
- Book appointments
- Join and track live queues
- Receive appointment and queue updates
- Access prescriptions and consultation information
- Navigate through a responsive mobile experience

### Demo Video Url : https://www.upwork.com/att/download/portfolio/persons/uid/1957485115732395726/profile/projects/files/15df3fed-4527-4287-92e4-8567f875eff9
### Demo Video Url 2 :https://www.upwork.com/att/download/portfolio/persons/uid/1957485115732395726/profile/projects/files/76c4dd58-d400-44af-acf1-11cfbfc96b6f

### Doctor Web Application

The doctor-side platform enables doctors and clinic teams to:

- Manage scheduled appointments
- Handle walk-in patients
- Review active queues
- Update consultation status
- Coordinate patient flow
- Access operational information
- View appointment and queue analytics

### Backend and Real-Time System

The backend supports:

- Secure authentication and role-based access
- Doctor, patient, and appointment management
- Queue creation and status updates
- REST API communication
- WebSocket-based real-time synchronization
- Payment and prescription workflows
- Scalable service-based architecture

## Key Features

- Doctor and specialist discovery
- Appointment-slot booking
- Live queue tracking
- Walk-in and scheduled-patient management
- Real-time updates using WebSockets
- Secure payments
- Prescription access
- Role-based patient and doctor workflows
- Doctor-side operational dashboard
- Mobile-friendly user experience

## Technology Stack

| Layer | Technology |
|---|---|
| Mobile Application | React Native |
| Doctor Web Application | React.js / Shadcn UI |
| Backend | NestJS |
| APIs | REST APIs |
| Real-Time Communication | WebSockets |
| Authentication | Secure role-based access |
| Payments | Payment gateway integration |
| Development Tools | Git, GitHub, Postman |

## System Architecture

```text
Patient Mobile App
        │
        │ REST APIs + WebSockets
        ▼
    NestJS Backend
        │
        ├── Appointment Service
        ├── Queue Management
        ├── Payment Workflows
        ├── Prescription Workflows
        └── User and Role Management
        │
        ▼
Doctor Web Application
