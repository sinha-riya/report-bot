# Know Your Diet App
This Streamlit application analyzes medical reports uploaded by users, providing insights and recommendations related to health and diet based on artificial intelligence models.

## Overview
The application integrates with Google's Generative AI platform to perform the following tasks:

#### Medical Report Analysis:
Upload medical images and extract information using the gemini-pro-vision model.
#### Abnormality Detection: 
Determine if the medical report indicates any abnormalities.
#### Diet Recommendation:
Based on the report analysis, provide a diet plan and schedule tailored to the user's health needs.
## Setup
#### Prerequisites
- Python 3.x installed on your system.
- Pip package manager.
- Google API key for accessing generative AI models (configured in config.json).
#### Installation
Clone the repository:
```
git clone <repository_url>
cd <repository_name>
```
#### Install dependencies:
```
pip install -r requirements.txt
```
#### Configuration
Obtain a Google API key and add it to config.json in the following format:

>json
```
{
    "GOOGLE_API_KEY": "your_api_key_here"
}
```
Customize the application as needed by modifying config.json and adjusting the prompts and responses in the script.

#### Usage
Run the application by executing the Python script:

```
streamlit run your_script.py
```
Upload a medical report image (.jpg, .jpeg, .png) and click "Upload".
The application will process the report, extract information, and provide insights and recommendations based on the analysis.