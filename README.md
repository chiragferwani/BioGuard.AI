# BioGuard.AI

### Revolutionizing Healthcare with AI

BioGuard.AI is a comprehensive AI-powered health assistant designed to provide medical information, predict diseases, and assess mental health. Developed as part of the **Living Knowledge Systems Decentralized AI Hackathon**, this project aims to improve accessibility to healthcare information through AI-driven insights.

## 🚀 Project Overview

**BioGuard.AI** offers three primary modules:
1. **MedGuard**: Enter a medicine name to get details about its uses and find alternative medicines with similar properties.
2. **PredictGuard**: Input your symptoms and receive AI-powered predictions of potential diseases and their treatments.
3. **MindGuard**: Take a short mental health assessment to receive insights into your psychological well-being.

## 🔧 Technologies Used

The project utilizes the following technologies:
- **Frontend**: HTML, CSS, JavaScript, SCSS, and Bootstrap for a responsive and intuitive user interface.
- **Backend**: Python for AI model creation, integrated using StreamLit cloud platform.
- **Deployment**: StreamLit cloud for hosting the AI modules.

## 📁 Project Structure

```
BioGuard.AI/
│
├── frontend/
│   ├── index.html        # Main HTML file
│   ├── styles.css        # Main CSS file
│   ├── app.js            # JavaScript functionality
│   └── assets/           # Logo, images, etc.
│
├── backend/
│   ├── MedGuard.py       # Medicine Information module
│   ├── PredictGuard.py      # Disease Predictor module
│   ├── MindGuard.py      # Mental Health Predictor module
│   └── requirements.txt  # Python dependencies
│
└── README.md             # Project documentation
```

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.7+
- Node.js
- StreamLit for backend hosting
- Tailwind CSS or Bootstrap for frontend styling

### Steps to Run Locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/BioGuardAI.git
    cd BioGuardAI
    ```

2. **Frontend Setup**:
    - Navigate to the `frontend` directory.
    - Open `index.html` in a browser or serve it with a local server.

3. **Backend Setup**:
    - Navigate to the `backend` directory.
    - Install required Python dependencies:
      ```bash
      pip install -r requirements.txt
      ```
    - Run the StreamLit app:
      ```bash
      streamlit run MedGuard.py  # Similarly for SympGuard.py and MindGuard.py
      ```

4. **Integrating Backend with Frontend**:
    - Adjust API endpoints or integration as needed.

## Features

- **MedGuard**: Provides medicine information and alternative suggestions.
- **PredictGuard**: Analyzes patient symptoms to predict potential diseases.
- **MindGuard**: Assesses mental health and provides insights.
- **FitGuard**: Takes user inputs to suggest personalized fitness and diet plans.
- **RescueGuard**: Offers emergency contacts and hospital locations based on user input.
- **FundGuard**: Provides quick loan services for medical emergencies.


## 💡 Advantages

- **AI-Driven Insights**: Quick access to health information and predictions through advanced AI.
- **User-Friendly Interface**: Simple and intuitive design with a focus on usability.
- **Accessibility**: Helps bridge the gap between patients and reliable healthcare information.
