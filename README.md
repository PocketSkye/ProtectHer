ProtectHer - Real-Time Women's Safety Solution
ProtectHer is a deep learning-based real-time safety application designed to help ensure women's safety using computer vision and natural language processing techniques. The solution integrates multiple models, including gender classification, facial emotion recognition (FER), and harassment detection, along with a fine-tuned GPT-2 Medium chatbot for dynamic user interactions.

Features
Gender Classification: Detects the gender of individuals in real-time through computer vision.
Facial Emotion Recognition (FER): Analyzes facial expressions to detect emotional states, helping identify distress or safety concerns.
Harassment Detection: Identifies potential harassment behaviors using visual cues.
Chatbot: A fine-tuned GPT-2 Medium-based chatbot provides dynamic, context-aware conversations to assist users and offer safety tips.
Interactive Mapping: Real-time location tracking with the Leaflet library for mapping user interactions and safety alerts.
Technologies Used
Deep Learning (CV): Convolutional Neural Networks (CNN) for image and video processing.
TensorFlow: Model training and deployment.
Flask: Backend framework for efficient model inference and API management.
Streamlit: For easy deployment and model inference interfaces.
GPT-2 Medium: Fine-tuned for creating an interactive chatbot for real-time communication.
HTML, CSS, JavaScript: Frontend development for a responsive and user-friendly interface.
Leaflet.js: For interactive maps and geolocation features.
Installation
Clone the repository:

git clone https://github.com/PocketSkye/ProtectHer.git
cd ProtectHer
Set up a virtual environment:

python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install required dependencies:

pip install -r requirements.txt
Run the Flask application:

python app.py
Access the web app:
Open your browser and navigate to http://localhost:5000.

Usage
Real-time Safety Monitoring: The system continuously processes live video feeds to identify safety concerns.
Chatbot Interaction: The integrated fine-tuned GPT-2 Medium chatbot offers contextual advice and safety tips based on user input.
Map Interaction: Use the interactive map to track and manage safety incidents in real-time.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-name).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-name).
Create a new pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.