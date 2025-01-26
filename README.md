# Google-Docs-creation-and-formatting-using-Python
**BRIEF DESCRIPTION**
This project demonstrates  a Python-based solution running in Google Colab converts markdown meeting notes into a well-formatted Google Doc. It creates a new document using the Google Docs API and then applies particular formatting styles including headings, bullet points, checkboxes, and mentions to ensure that the page follows preset styling requirements.
**SETUP INSTRUCTIONS**
**1**. Enable Google Docs API:
Go to Google Cloud Console.
Create a new project.
Navigate to APIs & Services > Library.
Search for Google Docs API and click Enable.
**2**.Create Credentials:
Go to APIs & Services > Credentials.
Click Create Credentials > OAuth 2.0 Client ID.
Configure the consent screen, download the credentials.json file, and save it locally.
**3**.Open Colab Notebook:
Access Google Colab.
Create a new notebook and upload your credentials.json file.
**4**.Install Required Libraries:
Run the following command in a code cell:
!pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
**5**.Authenticate Colab:
Add the following code to authenticate your Colab environment:
from google.colab import auth
auth.authenticate_user()
**6**.Run the Notebook:
Follow the steps in the notebook to execute the script.
**REQUIRED DEPENDENCIES**
The following Python libraries are required:
google-auth
google-auth-oauthlib
google-auth-httplib2
google-api-python-client
Install them using:
pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
**HOW TO RUN IN COLAB**
**1**.Upload credentials.json:
Use the following code in Colab to upload the file:
from google.colab import files
files.upload()
**2**.Authenticate:
Authenticate with Google Docs API by running:
from google.colab import auth
auth.authenticate_user()
**3**.Run the Notebook:
Execute the code cells sequentially to:
Authenticate Colab with Google Docs API.
Create a new Google Doc.
Parse the markdown notes.
Apply the specified formatting styles.

