Initial notebooks for detection, tracking, and landscape projection in the context of bears hunting salmon.

Relies on the [koger_detection](https://github.com/benkoger/detection-projects) package. See the corresponding readme for instructions for locally pip installing this package.

All dependencies are specified in the [requirements.txt](https://github.com/benkoger/bear-hunting/blob/main/requirements.txt) file except for torch which should be installed to match your specific machine (i.e. operating system, CPU or GPU etc.) following the instructions here: https://pytorch.org/get-started/locally/ This repo has been tested with torch==2.3.1+cu121 and python3.10
Install all dependencies at once by with ```pip install -r requirements.txt```

The following environmental variables are expected to be specified in a .env file.
ROOT is the path to main folder for this repo.
PROJECT_DROPBOX is the path to the dropbox folder for this project.

![pix4d](media/pix4d-point-cloud-example.png)


![ortho-hunt](media/Screenshot-of-ortho-video-bear-hunt.png)