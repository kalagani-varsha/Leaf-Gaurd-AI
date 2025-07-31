🌿 Important Instructions – Please Read Carefully:



This is a fully functional plant disease detection web app that is already deployed on the Heroku cloud platform. If you wish to run this project locally or deploy it yourself, follow the instructions below:

Local Setup Instructions:

\- Make sure you have Python installed.

\- Install all the dependencies listed in the requirements.txt file.

  Run this command in your terminal:

  pip install -r requirements.txt

\## 🔍 Model File (Not Included)



The model file `plant\_disease\_model\_1\_latest.pt` is \*\*not included\*\* in this repository due to GitHub's 100 MB file size limit.



&nbsp;Deployment:

\- A Profile is required to deploy the app on Heroku. This tells Heroku how to run your application.

\- Ensure that the file "plant\_disease\_model\_1\_latest.pt" (your trained model) is present in the root directory of the project.

\- If you train the model on your machine, simply drag and drop the .pt file into this project folder before deployment.



Model Notes:

\- Before running the app, visit the "Model" section of this repository to understand the model architecture and how it's used in the app.

\- If you decide to change the model filename, update the filename reference in app.py accordingly (look for the model loading line).



Additional Notes:

\- The app uses a PyTorch model for prediction, so make sure you have compatible versions of torch, torchvision, etc.

\- After setting up, you can launch the app locally and test it before deploying.

\- You can extend the model with more plant diseases by training on a larger dataset and replacing the existing .pt file.

