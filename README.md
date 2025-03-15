# WildEye
WildEye is a Python-based application that utilizes machine learning models to identify and classify animals in images. The project leverages pre-trained models and custom scripts to detect various animal species, providing a user-friendly interface for seamless interaction.

### Features
- Image Upload: Allows users to upload images for animal detection.
- Animal Classification: Utilizes machine learning models to identify and classify animals within the uploaded images.
- User Interface: Provides a simple and intuitive interface for users to interact with the application.

### Technologies Used
- Python: Programming language used for application development.
- Flask: Web framework for building the web application.
- TensorFlow: Machine learning framework for model deployment.
- OpenCV: Library for image processing tasks.
- HTML/CSS: For designing the web interface.

### Installation
To run the project locally, follow the steps below:

#### Clone the Repository:


    git clone https://github.com/JimmYCHUU/WildEye.git
Navigate to the Project Directory:


    cd animal-detector
#### Set Up the Virtual Environment:

It is recommended to use a virtual environment to manage dependencies:


    python3 -m venv env
    Activate the Virtual Environment:

##### On Windows:

    .\env\Scripts\activate
##### On macOS/Linux:

    source env/bin/activate
#### Install Dependencies:

##### Install the required Python packages:


    pip install -r requirements.txt
##### Install System Dependencies:

Some system libraries are required for the application to function correctly:

    sudo apt-get update && sudo apt-get install ffmpeg libsm6 libxext6
#### Run the Application:

##### Start the Flask development server:

    python app.py
The application will be accessible at http://127.0.0.1:5000/.

#### Usage
- Open the application in your web browser.
- Upload an image using the provided upload interface.
- The application will process the image and display the detected animal species.

#### Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.
