Details :
Team Member 1:
Name: Aaqeeb Pinjari
Country of Residence : Aurangabad, India
Graduation Year: 2024

Team Member 2:
Name : Aniket Andhale
Graduation Year: 2025
Experience Level : Student

Theme : Creating a brighter future for health by leveraging cutting-edge technology and compassionate care. Unleash the potential of AI to drive impactful solutions and foster a healthier tomorrow for all.

Problem Statement: The existing methods of diagnosing brain tumors through MRI scans often involve time-consuming and error-prone manual analysis by medical professionals. Additionally, there is a need for a secure and privacy-centric approach to handling sensitive patient data during the diagnostic process. 

Solution: In light of these challenges, Medalgnosis aims to create an intelligent and privacy-focused solution that revolutionizes brain tumor diagnosis using AI-driven analysis. By leveraging the power of Azure Custom Vision, the application seeks to empower patients with comprehensive tumor insights and personalized treatment recommendations, ultimately contributing to improved patient outcomes and enhanced brain health care.

Neuro Tech Care is an innovative medical software application designed to revolutionize brain tumor diagnosis through AI-driven MRI analysis.
Leveraging Azure Custom Vision's pre-trained machine learning model, the app accurately identifies Meningioma, Glioma, and Pituitary tumors and other diseases from uploaded MRI scans.
The platform ensures privacy by not storing any user data or MRI scans, safeguarding sensitive medical information through Streamlit.
With a user-friendly interface built using Streamlit, patients can easily upload MRI scans and receive rapid and precise tumor identification results.
Detailed insights about the detected tumor, including its characteristics, causes, effects, and potential treatments, are provided to enable informed decision-making.
Personalized treatment recommendations based on the tumor type and stage empower patients to make the best healthcare choices.
Medalgnosis streamlines appointment booking with specialized doctors through its integrated Azure Logic App, facilitating seamless communication.
The app's focus on data privacy, accuracy, and efficiency contributes to early detection and timely intervention, improving patient outcomes and brain health care.



Tech Stack: The following tech stacks have been used to create the application and deploy it.
Python to build the application.
Streamlit to create a responsive web application along with widgets.
Streamlit Community Cloud to deploy the web application for anyone across the globe to access it.
Microsoft Azure AI Custom Vision to get a computer vision model trained using our dataset and use it to predict the tumor type with the patient's MRI scan.
GitHub to host the source code, use the version control (collaboration history), pull requests and GitHub collaboration features.




Installation Guide: ⬇️
First, install the following:    Python

Then, follow this step-by-step process to run this application:
1. Get your Azure subscription: https://azure.microsoft.com/en-in/free
2. Create an Azure Custom Vision resource and train the model
3. Create the Azure Logic App Resource and add HTTP/HTTPS Trigger and send email (V2) action with the body as input for the trigger function.
or
Install the required dependencies to run the project:    pip install -r requirements.txt
Replace the endpoint and key with your Azure Custom Vision model resource endpoint and key in predictor.py.
Replace the logic app URL with the Azure logic app URL of the trigger in predictor.py.
Run the application by changing the drive to main folder and run the following the command in the terminal: streamlit run about.py in terminal
