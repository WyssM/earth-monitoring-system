# Earth Monitoring System

Real-time Earth monitoring application using NASA APIs with Spring WebFlux and Angular 20.

![Java](https://img.shields.io/badge/Java-25-orange?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4-green?style=flat-square)
![Angular](https://img.shields.io/badge/Angular-20-red?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

## Features

- **Live Earth View**: Real-time imagery from DSCOVR satellite via NASA EPIC API
- **Wildfire Tracking**: Interactive map with real-time wildfire data using FIRMS API
- **Satellite Imagery**: View satellite images of any coordinates on Earth
- **Time-lapse**: Environmental changes visualization over time
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Tech Stack

### Backend
- **Java 25** - Latest Java LTS
- **Spring Boot 3.4+** - Application framework
- **Spring WebFlux** - Reactive programming
- **WebClient** - Non-blocking HTTP client
- **Lombok** - Reduce boilerplate code
- **Caffeine Cache** - High-performance caching

### Frontend
- **Angular 20** - Modern web framework
- **Angular Material** - UI component library
- **Leaflet** - Interactive maps
- **RxJS** - Reactive programming
- **Signals** - Angular's reactivity system
- **Standalone Components** - Modern Angular architecture

### APIs Used
- **NASA EPIC** - Earth Polychromatic Imaging Camera
- **NASA Earth Imagery** - Landsat 8 satellite imagery
- **FIRMS** - Fire Information for Resource Management System

## 🚀 Getting Started

### Prerequisites

- Java 25
- Node.js 20+ and npm
- Git
- NASA API Key (from https://api.nasa.gov/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/earth-monitoring-system.git
   cd earth-monitoring-system
   ```

2. **Backend Setup**
   ```bash
   cd backend
   # Configure NASA API key in application.yml
   ./mvnw spring-boot:run
   ```
   Backend runs on http://localhost:8080

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   ng serve
   ```
   Frontend runs on http://localhost:4200

## Documentation
- [Backend Documentation](./backend/README.md)
- [Frontend Documentation](./frontend/README.md)
- [API Documentation](./docs/API.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
