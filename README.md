# ElecGad

## Your Personal Assistant for Easy Offline Electronics & Gadget Purchases

ElecGad is an AI-powered assistant that helps users make informed offline electronics purchases. Instead of spending hours comparing products and searching for stores, users can interact with ElecGad to receive personalized recommendations based on their budget, preferences, and location.

---

## Live Application

### Frontend
[Frontend Deployment](YOUR_VERCEL_URL)

### Backend API
[Backend Deployment](YOUR_RENDER_URL)

---

## Project Repositories

### Frontend Repository
[ElecGad Frontend](YOUR_FRONTEND_REPO_URL)

### Backend Repository
[ElecGad Backend](YOUR_BACKEND_REPO_URL)

---

## Problem Statement

Purchasing electronics offline can be challenging because customers often:

- Do not know which brands to consider.
- Get overwhelmed by too many model choices.
- Struggle to compare features within a budget.
- Spend significant time locating nearby stores.
- Lack access to expert guidance during the buying process.

ElecGad addresses these issues through an AI-guided recommendation workflow.

---

## Features

### Budget-Based Recommendations
Users specify the gadget they want and their budget range.

### Brand Suggestions
AI recommends suitable brands within the selected budget.

### Model Recommendations
AI provides model suggestions from the selected brands.

### Location-Based Store Suggestions
Users provide their location and receive nearby store recommendations.

### Purchase Summary
ElecGad generates a consolidated summary of the user's choices.

### Electronics Help Mode
Users can ask additional electronics-related questions after completing the workflow.

### Domain Restriction
The assistant focuses only on electronics and gadget-related topics.

---

## Workflow

```text
User enters Gadget + Budget
            ↓
AI suggests Brands
            ↓
User selects Brands
            ↓
AI suggests Models
            ↓
User selects Models
            ↓
User enters Location
            ↓
AI suggests Stores
            ↓
Summary Generation
            ↓
Electronics Help Mode
```

---

## Technology Stack

### Frontend

- React
- Vite
- Axios
- React Markdown
- CSS

### Backend

- FastAPI
- Uvicorn
- Python

### AI

- Google Gemini API

### Deployment

- Vercel (Frontend)
- Render (Backend)

---

## Project Structure

```text
ElecGad
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── app.py
│   ├── ai.py
│   ├── assistant.py
│   ├── prompts.py
│   └── requirements.txt
│
└── README.md
```

---

## User Journey Example

```text
User: Laptop under ₹60,000

AI:
Recommended Brands:
- Lenovo
- HP
- ASUS

User: Lenovo, HP

AI:
Recommended Models:
- Lenovo IdeaPad Slim 3
- HP 15s

User: Chennai

AI:
Nearby Stores:
- Reliance Digital
- Croma
- Poorvika

User: Yes

AI:
Generates final purchase summary.
```
## Screenshots

### Home Page

![ElecGad Home Page](homepage.png)
---

## Key Learnings

This project helped in understanding:

- AI-assisted workflow design
- Prompt engineering
- Session state management
- FastAPI backend development
- React frontend development
- REST API integration
- Deployment using Render and Vercel
- CORS configuration and debugging
- Gemini API integration

---

## Future Improvements

- Real-time product pricing
- Online store integration
- User authentication
- Product comparison tables
- Review aggregation
- Multi-language support
- Persistent chat history

---

## Author

### Nitin Anand A

Final Year B.Tech Student

Project: ElecGad – Your Personal Assistant for Easy Offline Electronics & Gadget Purchases

---

## License

This project is intended for educational and portfolio purposes.
