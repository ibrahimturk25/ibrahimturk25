# Volley App

<p align="center">
  <img src="assets/logo.png" alt="Volley App Logo" width="120" />
</p>

<p align="center">
  A full-stack volleyball community platform serving <strong>30,000+ active users</strong> on iOS and Android.
</p>

<p align="center">
  <a href="https://apps.apple.com/tr/app/volley-app/id6751442243">
    <img src="https://img.shields.io/badge/App%20Store-Download-blue?logo=apple" alt="App Store" />
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.ibrahimturk.volleyApp">
    <img src="https://img.shields.io/badge/Google%20Play-Download-green?logo=google-play" alt="Google Play" />
  </a>
  <img src="https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter" alt="Flutter" />
  <img src="https://img.shields.io/badge/.NET-8.0-purple?logo=dotnet" alt=".NET 8" />
  <img src="https://img.shields.io/badge/Azure-Live-blue?logo=microsoft-azure" alt="Azure" />
</p>

---

## Overview

Volley App is a production volleyball community platform built and maintained by a single developer, covering the full stack from mobile UI to cloud infrastructure. Users can follow live matches in real time, chat with other players, manage team rosters, and track personal statistics — all within a single app.

The project was built with a focus on production reliability, security, and scalability from day one.

---

## Features

- **Live Match Tracking** — Real-time score updates and match events via SignalR
- **Instant Messaging** — Live chat rooms powered by SignalR websockets
- **Push Notifications** — Advanced FCM notification system for match alerts, messages, and announcements
- **Secure Authentication** — JWT + Refresh Token rotation, Google OAuth, BCrypt password hashing
- **Role-Based Access** — Separate Admin and User flows with fine-grained permissions
- **Payment Integration** — In-app purchase and subscription support
- **User Statistics** — Detailed match history, performance metrics, and player profiles
- **Scheduled Jobs** — Background automation via Hangfire (reminders, cleanup, aggregations)
- **Centralized Logging** — Serilog + Azure Application Insights for production monitoring

---

## Tech Stack

### Mobile (Flutter)

| Layer | Technology |
|-------|-----------|
| Framework | Flutter (Dart) |
| Architecture | MVVM + Clean Architecture |
| HTTP Client | Dio |
| Real-Time | SignalR |
| Notifications | Firebase Cloud Messaging (FCM) |
| Auth | Firebase Auth + JWT |
| State Management | Provider / MVVM pattern |

### Backend (.NET)

| Layer | Technology |
|-------|-----------|
| Framework | .NET 8.0 (ASP.NET Core) |
| ORM | Entity Framework Core |
| Database | SQL Server |
| Cache | Redis |
| File Storage | Azure Blob Storage |
| Background Jobs | Hangfire |
| Logging | Serilog + Azure Application Insights |

### Security

| Concern | Implementation |
|---------|---------------|
| Authentication | JWT + Refresh Token rotation |
| OAuth | Google OAuth 2.0 |
| Password hashing | BCrypt |
| Rate limiting | AspNetCoreRateLimit |
| Injection protection | XSS + SQL Injection filters |

### Infrastructure

| Service | Provider |
|---------|---------|
| Hosting | Microsoft Azure |
| CDN / Storage | Azure Blob Storage |
| Monitoring | Azure Application Insights |
| CI/CD | Azure Pipelines |

---

## Getting Started

### Prerequisites

- Flutter SDK 3.x
- .NET 8.0 SDK
- SQL Server (local or Azure SQL)
- Redis (local or Azure Cache for Redis)
- Firebase project (for FCM + Auth)
- Azure account (for Blob Storage + Application Insights)

### Mobile Setup




---

## Screenshots

> Coming soon — App Store screenshots available at [apps.apple.com/tr/app/volley-app/id6751442243](https://apps.apple.com/tr/app/volley-app/id6751442243)

---

## Production

The app is live and serving 30,000+ monthly active users.

- **iOS:** [App Store](https://apps.apple.com/tr/app/volley-app/id6751442243)
- **Android:** [Google Play](https://play.google.com/store/apps/details?id=com.ibrahimturk.volleyApp)
- **Backend:** Hosted on Azure App Service with auto-scaling
- **Monitoring:** Azure Application Insights dashboard for real-time error tracking and performance metrics

---

## Contributing

This is a personal production project. Issues and suggestions are welcome via GitHub Issues.

---

## Author

**İbrahim Türk**
- GitHub: [@ibrahimturk25](https://github.com/ibrahimturk25)
- LinkedIn: [ibrahim-türk-tr](https://linkedin.com/in/ibrahim-türk-tr)
- Email: ibrahimturk.ib@gmail.com

---

## License

This project is proprietary software. All rights reserved.
