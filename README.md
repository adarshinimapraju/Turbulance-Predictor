# Turbulance-Predictor
Turbu is an AI-powered web application that predicts flight turbulence using a combination of machine learning and physics-informed neural networks (PINNs). It leverages real-world aviation and weather data to help users understand turbulence patterns before and during a flight.

**🚀 Overview**

Air turbulence is influenced by complex atmospheric factors like wind speed, pressure, temperature, and altitude. Traditional models rely only on data, but Turbu improves prediction accuracy by also enforcing physical laws of fluid dynamics using PINNs.

The application allows users to:

Search for flights between two airports
Visualize the flight route on an interactive map
View past flight details and durations
Generate turbulence graphs for completed flights
Predict turbulence for upcoming flights using real weather data

**🧠 Core Idea**
Turbu uses a Physics-Informed Neural Network where:
One part learns from real flight and weather data
Another part ensures predictions obey physical equations

This improves reliability compared to standard ML models.

**Loss Function:**

Prediction Loss → Difference between predicted and actual turbulence
Physics Loss → Violation of physical laws (wind flow, pressure relations, etc.)
📊 Features
🌍 Global airport dataset integration
✈️ Flight route visualization on interactive map
📜 Past flight history with duration
📈 Turbulence intensity graph across journey
🔮 Future turbulence prediction using weather forecasts
⚠️ Risk classification (Low / Medium / High)
🤖 PINN-based hybrid AI model
