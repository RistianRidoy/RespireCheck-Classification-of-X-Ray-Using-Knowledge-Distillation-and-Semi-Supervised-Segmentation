# RespireCheck-Classification-of-X-Ray-Using-Knowledge-Distillation-and-Semi-Supervised-Segmentation
This web application leverages CLIP-KDViT and Grad-CAM to provide explainable chest X-ray diagnoses for COVID-19, pneumonia, and tuberculosis with high accuracy.
Features

    AI-powered Diagnosis: Automatically classifies chest X-ray images to detect COVID-19, pneumonia, and tuberculosis.
    Explainable AI: Uses Grad-CAM for visualizing and understanding model predictions.
    High Accuracy: Achieves high diagnostic accuracy through advanced deep learning techniques.

Requirements

Before running the project locally, ensure you have the following:

    Python 3.x (preferably Python 3.7 or higher)
    Virtual Environment (venv)

Steps to Deploy the Web Application
1. Create a Virtual Environment:

Create a new virtual environment in your local environment to isolate the dependencies required for this project.

python -m venv venv

2. Activate the Virtual Environment:

    On Windows:

.\venv\Scripts\activate

On MacOS/Linux:

    source venv/bin/activate

3. Install Required Libraries:

After activating the virtual environment, install all the necessary Python frameworks and dependencies from requirements.txt.

pip install -r requirements.txt

The requirements.txt file should include all the necessary dependencies for running the app, such as:

    Flask
    torch
    torchvision
    PIL
    numpy
    opencv-python
    grad-cam
    And any other specific libraries used in the project.

4. Upload Model Files:

Due to the size of the model.pth files, you need to upload them on your own. The pre-trained model files are required for making predictions but are too large to upload directly to the repository.

Once you have the model.pth files, place them in the appropriate directory of the project (e.g., ./models/).
5. Run the Web Application:

Once the virtual environment is set up and the necessary model files are in place, you can run the web application.

python app.py

This will start the web server, and you can access the application via:

http://127.0.0.1:5000

Contributing

Feel free to fork the repository and submit issues or pull requests. Contributions are welcome!
License

This project is licensed under the MIT License - see the LICENSE file for details.
Key Points:

    Virtual Environment: It’s essential to create and activate a virtual environment to install the dependencies.
    Model Files: The model.pth files are too large to upload to GitHub, so users need to upload them in their local setup. Make sure to place them in the appropriate folder (e.g., ./models/).
    Running the Web Application: Users can run the application with python app.py after setting up the environment.

This README structure provides clear instructions for setting up the project locally, including the handling of large model files that cannot be uploaded to GitHub. Let me know if you need any additional modifications!
