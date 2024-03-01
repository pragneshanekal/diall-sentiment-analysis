# diall-sentiment-analysis

## Overview
The system is designed to analyze sentiments of clients and understanding the emotional dynamics of their sessions. By leveraging NLP and AutoML techniques, the system attempts to provide insights into the sentiments expressed during sessions and offer predictive insights to anticipate future trends.

## Dataset
The dataset used in this system has been simulated for demonstration purposes. It includes data for 10 sessions of a single patient. Each session contains:

- Assessment scores: Numeric scores recorded by the therapist to evaluate the patient's progress.
- Session notes: Any additional notes or observations made by the therapist during the session.
- Transcripts: Textual transcripts of the interactions between the therapist and the patient during each session.
Please note that this dataset is generated for illustrative purposes and may not reflect real patient data.

## Functionality

### Sentiment Analysis
The system performs sentiment analysis on the transcripts of each session using NLTK. It evaluates the emotional tone of the conversation and categorizes it as positive, negative, or neutral. It prioritizes more recent sessions by giving higher importance to sentiments expressed in latest sessinos as opposed to sentiments of earlier sessions.

### Trend Visualization
The system visualizes sentiment trends over the 10 sessions, allowing therapists to identify patterns and fluctuations in the patient's emotional state. Graphical representations provide an intuitive way to interpret the data and track progress over time.

### Predictive Analytics
Using H2O's AutoML capabilities, the system generates predictive models based on the historical session data. These models forecast future sentiment trends and enable therapists to anticipate potential shifts in the patient's emotional well-being. Predictive analytics empower therapists to take proactive measures and tailor their interventions accordingly.

*Note:* It's important to note that due to the relatively small size of the dataset, the accuracy of the AutoML predictions may be limited. Further optimization and refinement of the predictive models are necessary to improve accuracy and reliability.
