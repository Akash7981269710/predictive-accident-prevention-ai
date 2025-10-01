# predictive-accident-prevention-ai
An AI-powered predictive accident prevention system that uses machine learning to estimate accident risk based on weather, road, traffic, and visibility conditions.
predictive-accident-prevention-ai-java
│── src/
│   └── TrainModel.java      # Train ML model using Weka
│   └── Predictor.java       # Loads trained model and predicts risk
│   └── Main.java            # JavaFX app for user input
│── data/
│   └── accidents.csv        # Sample dataset
│── model/
│   └── accident.model       # Saved trained model
│── pom.xml                  # Maven dependencies (Weka, JavaFX)
│── README.md                # Project documentation
│── .gitignore
