# M-Guard Health Monitoring System

M-Guard is a comprehensive health monitoring system that combines AI-powered cuff detection, real-time health metrics monitoring, and interactive chat capabilities. The system is built using modern web technologies and machine learning.

## System Architecture

The system consists of three main components:

### 1. Frontend (Next.js)

- Built with Next.js 15.2.3 and React 19
- Modern UI components using Radix UI
- Real-time updates using Socket.IO
- Authentication with NextAuth.js
- Styling with Tailwind CSS
- Form handling with React Hook Form
- Calendar integration with React Big Calendar
- Webcam integration for real-time monitoring

### 2. Backend (NestJS)

- RESTful API built with NestJS
- MongoDB integration with Mongoose
- Google OAuth authentication
- WebSocket support for real-time communication
- gRPC integration for AI services
- TypeScript for type safety
- Comprehensive testing setup with Jest

### 3. AI Services (Python)

- gRPC-based microservices
- Two main services:
  - Cuff Detection Service
    - Uses YOLO models for pose detection
    - Health metrics monitoring
    - Posture analysis
  - Chat Service
    - OpenAI integration
    - Streaming responses
- Docker support for deployment
- Computer vision with OpenCV
- Deep learning with PyTorch

## Key Features

1. **Real-time Health Monitoring**

   - Cuff position detection
   - Posture analysis
   - Health metrics tracking

2. **Interactive Chat**

   - AI-powered assistance
   - Streaming responses
   - Error handling

3. **User Interface**

   - Modern, responsive design
   - Real-time updates
   - Calendar integration
   - Webcam support



