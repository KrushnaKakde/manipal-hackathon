# Manipal Hackathon Project

Welcome to the Manipal Hackathon Project! This repository contains both the backend and frontend code for the project.

## Features
- Modern React frontend (with Tailwind CSS)
- Python backend (Flask/FastAPI-ready)
- MongoDB integration
- API endpoints for data queries and performance optimization
- User authentication (Sign Up, Login, Profile)

## Project Structure

```
Manipal-hackathon-project-main/
├── backend.env.example
├── optimize_performance.py
├── query_api.py
├── requirements.txt
├── simple_api.py
├── view_mongo_data.py
├── frontend/
│   ├── package.json
│   ├── tailwind.config.js
│   ├── src/
│   │   ├── App.js
│   │   ├── components/
│   │   └── pages/
│   └── ...
└── ...
```

## Getting Started

### Backend
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the backend server:
   ```bash
   python simple_api.py
   ```

### Frontend
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm start
   ```

## Environment Variables
- Copy `backend.env.example` to `.env` and fill in your configuration.

## Deployment
- The project is ready for deployment on platforms like Vercel (frontend) and any Python-compatible backend host.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)
