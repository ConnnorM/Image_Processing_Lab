# Image_Processing_Lab
- Experimenting with Python image processing to automate calculation of *insert name of cool underwater organism thingy here* surface areas.

# TODO:
- run the function on the photo using all possible threshold values
    - choose threshold value(s) that gets a count that is closest to example value
- repeat for all example photos to 'train' (determine threshold parameter)
    - use % error as loss function
- make a cropping gui...? or they can just do that on their own idk
- use nearest neighbors or something to get rid of outlier dots that aren't converted properly with threshold

## Notes
- After cloning this repository, set up the virtual environment using the instructions under the 'Virtual Environment' heading below
- Upload the original photos to the original_photos folder
- Black and white versions of the photos are created and saved to the black-white photos folder

## Virtual Environment
### Create Virtual Environment
- Open terminal/powershell/command prompt, navigate to this folder and type this command:
    - python -m venv .venv
- Now run this command:
    - pip install -r requirements.txt
### Activate Virtual Environment
- Before running the program, make sure to activate the virtual environment.
- Open terminal/powershell/command prompt, navigate to this folder, and type this command:
    - Windows command prompt
        - .venv\Scripts\activate.bat
    - Windows PowerShell
        - .venv\Scripts\Activate.ps1
    - macOS and Linux
        - source .venv/bin/activate
- To exit the virtual environment, type deactivate into the terminal