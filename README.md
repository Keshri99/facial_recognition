# facial_recognition
This is an intro to get started with facial recognition using Python
We shall leverage the [face_recognition](https://github.com/ageitgey/face_recognition) package in Python 
The hassle free way to get it running without any errors(for Windows):
- Create a 'virtualenv' in Python 
  - Install virtualenv if not already. Open command prompt : `py -m pip install --user virtualenv`
  - Create a new virtual environment `py -m venv <environment_name>`  
  - Activate the environment `.\<environment_name>\Scripts\activate` (notice your prompt changes with prefix of the environemnt name)
- Install [CMake] (https://cmake.org/download/) according to your system specs
  - We need CMake to get the `dlib` library working
  - Ensure that CMake is added to the path variable in the environment variables
  
  
