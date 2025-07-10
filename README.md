# What is this
This is from https://github.com/mpolinowski/yolov8-nightshift/

He trained both a YOLOv8n and YOLOv8s model for 1) only RGB images, 2) only IR images and 3) for the combined image dataset.

To detect cars, IR only did better than EO only^.  The combined dataset did about the same as IR only.  (The pattern is similar for people and other classes.)  Small models did better than nano models.

^ Probably b/c more images were collected at night than day or other hard conditions for RGB cameras (sun, smoke, fog, etc.)

# How to run

## Get the data.

See [link](https://adas-dataset-v2.flirconservator.com/#multipartdownloadsection).  

Put it in ./datasets

## Get conda envt. set up

## jupyter notebook --notebook-dir=`pwd`

## Open "http://localhost:8890" in a browser and type in the token from the command line

If using WSL, you can see files in Windows via \\wsl.localhost\Ubuntu-24.04

## Notes

Repo assumes lables to be in ...
Not there.
Possibly in https://www.kaggle.com/datasets/samdazel/teledyne-flir-adas-thermal-dataset-v2?resource=download or https://www.kaggle.com/code/kushagraborse/fusing-method-on-yolo-and-detection/notebook