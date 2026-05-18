#  Servante Intelligente

**An Intelligent Tool Management System for EMINES University**

An innovative tool management and lending system that combines RFID badge authentication, automated motorized drawer dispensing, and real-time inventory tracking.

##  Key Features

- **RFID Badge Authentication**: Secure access control using RFID technology
- **Automated Tool Dispensing**: Motorized drawers for efficient tool retrieval
- **Real-Time Inventory Tracking**: PostgreSQL database with comprehensive tool management
- **Multi-Language Support**: French and English interfaces
- **Admin Analytics Dashboard**: Detailed statistics and system monitoring
- **Borrow/Return System**: Complete tool lending workflow with user tracking
- **Hardware Integration**: Arduino-based RFID and motor control

##  Tech Stack

**Backend:**
- Node.js + Express + TypeScript
- PostgreSQL + Prisma ORM
- SerialPort (Arduino communication)
- JWT Authentication

**Frontend:**
- React + TypeScript
- Vite (build tool)
- Tailwind CSS
- Recharts (analytics)
- i18next (internationalization)

**Hardware:**
- Arduino Mega
- RC522 RFID Module
- 4x Stepper Motors for drawer control

##  Getting Started

### Prerequisites
- Node.js (v16+)
- PostgreSQL (v12+)
- Arduino IDE
- Docker (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/douaeelghazal/servante-intelligente.git
cd servante-intelligente
```

2. Install dependencies:
```bash
npm install
cd servante-backend && npm install
cd ../servante-frontend && npm install
```

3. Configure environment variables:
```bash
cp .env.example .env
```

4. Start the application:
```bash
docker-compose up
```

##  Documentation

- [Project Documentation](./PROJECT_DOCUMENTATION.md) - Complete system documentation
- [RFID Integration](./RFID_INTEGRATION_COMPLETE.md) - RFID setup and configuration
- [Motor Integration](./MOTOR_INTEGRATION.md) - Motor control setup
- [Admin Guide](./servante-backend/documents/guide_admin/)
- [User Guide](./servante-backend/documents/guide_utilisateur/)

##  License

MIT License

##  Institution

EMINES - Université Mohammed VI Polytechnique
