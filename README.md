# SafeMediDisposal

## Overview

SafeMediDisposal is a comprehensive web-based platform designed to tackle one of the most overlooked challenges in healthcare — the safe and sustainable disposal of biomedical waste. Built using modern full-stack technologies with AI integration, this solution empowers users with real-time tracking, intelligent waste classification, and gamified engagement to promote responsible waste management.

India generates approximately *710 tonnes of biomedical waste daily*, a significant portion of which is improperly segregated, disposed of, or even dumped illegally — risking infections, environmental hazards, and regulatory violations. SafeMediDisposal addresses this critical issue with a digital-first, AI-powered, people-centric approach that creates a complete ecosystem where hospitals, individuals, and authorities can collaborate for cleaner and safer healthcare practices.

*Live Demo*: [SafeMediDisposal](https://safemedidisposal1.netlify.app/)

## Tech Stack

### Frontend
- *HTML5* - Semantic page structure and layout
- *CSS3* - Custom styling and responsive design  
- *JavaScript* - Interactive functionality and UI behavior
- *Bootstrap 5* - Responsive components and utility classes
- *Font Awesome* - Icon library for enhanced UI clarity
- *Google Fonts* - Typography (Poppins & Fraunces)

### Backend
- *Node.js* - Server-side JavaScript runtime
- *Express.js* - Web application framework
- *MongoDB* - NoSQL database for data storage
- *JWT* - Secure user authentication
- *Roboflow AI API* - Medical waste detection and classification


## Features

### Core Innovations

*Real-time Dashboard*
A user-friendly dashboard providing complete control and visibility with real-time summary of today's waste, pickup statuses, top waste categories, and fulfillment insights. Offers clear, comprehensive view to track progress and monitor waste distribution trends.

*Smart Waste Scanner (AI-Powered)*
Instantly classify biomedical waste by uploading an image. The Waste Scanner, powered by ML Roboflow, detects specific items like masks, syringes, and IV bags, enabling accurate segregation that can reduce hospital costs by up to 40%.

*Scan & Score – Reward System*
Gamified engagement system where users earn eco-points for each scanned item and redeem them for sustainable kits, digital badges, or merchandise. Points can also be donated to health and environmental initiatives, promoting waste-conscious culture.

*RFID Waste Tracking*
Comprehensive accountability system preventing illegal dumping. Each waste bin or disposal bag is tagged with RFID chips, making the entire journey from hospital to treatment facilities completely traceable.

### Platform Features

*Eco Disposal Vision*
Strategic planning interface for smart hospital partnerships and future AI-based waste tracking implementations.

*Latest News Integration*
Curated content and headlines from health and environment domains to keep users informed about industry developments and policy changes.

*Campaign Management*
Comprehensive system for organizing and showcasing ongoing and past campaigns for public awareness and community engagement.

*Responsive Design*
Seamless and intuitive user experience optimized for all devices, from desktop to mobile platforms.

## Technical Workflow

### 1. User Authentication & Dashboard Access
- Users register/login through JWT-based authentication system
- Dashboard loads with real-time waste tracking data from MongoDB
- Role-based access control for different user types (hospitals, individuals, authorities)

### 2. AI-Powered Waste Classification

Image Upload → Roboflow API → Classification Results → Database Storage

- Users upload waste images through the web interface
- Images are processed by Roboflow AI API for automatic classification
- Classification results are stored in MongoDB with confidence scores
- Real-time feedback provided to users with waste category and disposal guidelines

### 3. RFID Tracking System

RFID Tag Assignment → Waste Collection → Transit Tracking → Final Disposal

- Each waste container receives unique RFID identifier
- Real-time location and status updates throughout disposal journey
- Blockchain-like audit trail for complete transparency
- Integration with hospital management systems for seamless tracking

### 4. Gamification & Rewards

Waste Scan → Point Calculation → User Account Update → Reward Redemption

- Points awarded based on waste type, accuracy, and frequency
- Leaderboard system for community engagement
- Integration with partner organizations for reward fulfillment
- Donation system for contributing points to environmental causes

### 5. Data Analytics & Reporting
- Real-time dashboard updates using WebSocket connections
- Automated report generation for compliance and auditing
- Predictive analytics for waste generation patterns
- Integration with government reporting systems

### 6. Campaign & News Management
- Content management system for campaign creation and tracking
- Automated news aggregation from reliable health/environment sources
- User engagement tracking and analytics
- Social media integration for broader outreach

*Impact Goals*: 40% reduction in hospital waste management costs, 100% waste traceability, enhanced community engagement, policy compliance support, and environmental protection through proper disposal practices.

## Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Git

### Installation

1. Clone the repository
bash
git clone https://github.com/LabhanshiBhatia/SafeMediDisposal_1.git
cd safemedisposal


2. Install dependencies
bash
npm install


3. Set up environment variables
bash
# Create .env file
cp .env.example .env

# Configure your environment variables
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
ROBOFLOW_API_KEY=your_roboflow_api_key


4. Start the development server
bash
npm start


5. For frontend-only development
bash
open index.html


The application will be available at http://localhost:3000



