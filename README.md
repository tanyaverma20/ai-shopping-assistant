# AI Shopping Assistant Platform

> An intelligent, full-stack e-commerce platform that combines **Generative AI (LLMs)** and **Machine Learning** to deliver personalized, conversational, and efficient shopping experiences.

## Overview
Traditional e-commerce platforms rely on manual search and filtering.  
This project transforms that experience by enabling **AI-driven product discovery**, where users can interact naturally and receive intelligent, personalized recommendations.

##  Key Features
### Core E-commerce
- User authentication (JWT + OAuth)
- Product browsing, filtering, sorting
- Product detail pages with reviews
- Cart & checkout system
- Order tracking & history
- Secure payment integration (Stripe/Razorpay)

### Generative AI (LLM Features)
- **Conversational Shopping Assistant**  
  Natural language queries like:  
  *“Suggest budget-friendly running shoes under ₹2000”*

- **Multi-step Reasoning**  
  AI compares products and explains recommendations  

- **Semantic Search**  
  Understands intent beyond keywords  

- **AI Review Intelligence**  
  Summarizes reviews into pros, cons, and sentiment  

### Machine Learning Features
- **Recommendation System**
  - Collaborative filtering
  - Content-based filtering
  - Personalized suggestions
- **Sentiment Analysis**
  - Classifies reviews (positive/negative)
  - Improves product ranking
- **Demand Prediction (Optional)**
  - Identifies trending products

## Tech Stack
### Frontend
- React.js / Next.js
- Tailwind CSS
### Backend
- Node.js
- Express.js
### Database
- MongoDB
### AI Layer
- OpenAI API (LLM-based features)
### ML Layer
- Python (Scikit-learn, Pandas, NumPy)

## System Architecture
Client (React / Next.js)
        ↓
Backend API (Node.js / Express)
        ↓
Database (MongoDB)
        ↓
AI Layer (OpenAI API)
        ↓
ML Models (Recommendation, Sentiment)

## Performance Optimizations

- Redis caching for faster responses  
- Indexed database queries  
- Reduced API latency from ~800ms → ~300ms  

## Security
- JWT-based authentication  
- Password hashing (bcrypt)  
- Input validation & rate limiting  
- Secure API handling  

## Demo
> Add screenshots / demo video / live link here

## Installation
```bash
git clone https://github.com/your-username/ai-shopping-assistant
cd ai-shopping-assistant
npm install
npm start
