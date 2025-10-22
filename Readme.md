# Project Title
# HybridAuthentica 
## Quantum-Enhanced Deepfake Triage for Safer Digital Spaces

## Team Members
- Ayana Ndete 
- Nelly Nyadzua
- Ann Miano

---

## Concept Description
HybridAuthentica is a hybrid deepfake detection and triage system designed to enhance online safety by identifying manipulated media that contributes to misinformation and harassment.  
The project addresses the growing challenge of distinguishing authentic content from synthetic deepfakes used in reputational harm, digital blackmail, and political disinformation.  

While most current detection systems rely purely on classical machine learning models, HybridAuthentica combines **classical pre-filtering** and **quantum verification**.  
This approach enables scalable and efficient early detection while exploring the use of quantum-enhanced pattern recognition for higher forensic accuracy.

---

## How the Solution Works
The system operates through three coordinated layers:

1. **Ingestion Layer (FastAPI)**  
   Users upload an image or video through an API endpoint. The system automatically generates a unique file hash and runs a quick authenticity check.

2. **Classical Pre-filtering (Machine Learning)**  
   A lightweight AI model extracts visual and temporal features from the media to produce a preliminary deepfake probability score. If the score is high, the file is flagged for deeper analysis.

3. **Quantum Verification (Qiskit Variational Quantum Classifier)**  
   The flagged data is encoded into a quantum circuit using Qiskit. The Variational Quantum Classifier (VQC) analyzes subtle correlations in the data, improving the precision of detection beyond what classical systems can achieve.

Output is returned in JSON format, showing a preliminary score and status (e.g., “queued for heavy verification”).  
This allows the framework to be scaled both for **platform-level moderation** and **personal digital safety applications**.

---

## Demo / Screenshots
Below is a simplified architectural representation of HybridAuthentica:


│ Media Ingestion (API) │ ← FastAPI backend

                   
│ Pre-filter & Feature Extraction (ML) │

                     
│ Quantum VQC │ ← Deepfake verification via Qiskit│

         
│ Results Queue │

           
│ Report / Dashboard │


We also have a few screenshots:

![WhatsApp Image 2025-10-22 at 21 57 45_184213bf](https://github.com/user-attachments/assets/59b91c0f-0559-4301-97b4-7e12e873a4ed)
It showcases our sample landing page where we can upload our mp4 videos for analysis.

![WhatsApp Image 2025-10-22 at 21 58 06_d996383b](https://github.com/user-attachments/assets/f4c55987-ae8f-442d-bc34-079870f14ccb)
It showcases a sample deepfake video as input and the output we get.


And finally we have our demo video :

https://github.com/user-attachments/assets/63ef2d30-8ce5-49cf-a1c5-0d686fd33a97

## Github link
Github link:

https://github.com/MI-AN-O/HybridAuthentica.git






