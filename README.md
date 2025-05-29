# AI powered Health Diagnose Agent using llama3.1
Health Diagnose Agent generates diagnosis for patient symptoms by referring internal hospital database (RAG) and validating through hospitals official sites (RAG) with accuracy Ratings of generated diagnosis. It is safer to check with official hospital Agents for symptoms rather trusting public domains.

# Features:
Research the symptoms with internal database using RAG and generate diagnosis.

Validates the generated diagnosis using official hospital sites and provides accuracy rating of the generated diagnosis.

Utilizes the power of llama3.1 to generate intelligence and provide suggestions of diagnosis, appointment booking with positive notes.

# Requirements
Install the required dependencies:

pip install openai

pip install pyautogen

pip install langchain-community

# How it Works?
The AI Health Diagnose Agent has 4 main components:

Symptoms_agent - Collects patients Name, Age, Gender, symptoms and symptoms duration.

Diagnose_Agent - Generate Diagnosis by referring internal database (Uses RAG).

Validator_Agent - Validates diagnosis by referring official hospital site (Uses RAG) and provide accuracy for diagnosis from 1 to 5, where 1 is low and 5 is high.

Health_Assistant_agent - Summarizes the diagnosis and validation and help patient to book appointment with positive notes.
