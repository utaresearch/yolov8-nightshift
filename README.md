# What is this
This is from https://github.com/mpolinowski/yolov8-nightshift/

He trained both a YOLOv8n and YOLOv8s model for each case - only RGB images, only IR images and for the combined image dataset.

To detect cars, IR only did better than EO only^.  Combined did about the same as IR only.  The pattern is similar for person and other classes.  Small models did better than nano models.

^ Probably b/c more images were collected at night than day or other hard conditions for RGB cameras (sun, smoke, fog, etc.)

# How to run

## get the data.

See [link](https://adas-dataset-v2.flirconservator.com/#multipartdownloadsection).  

Put it in ./dataset

## get conda envt. set up

## jupyter notebook --notebook-dir=`pwd`

## Open "http://localhost:8890" in a browser and type in the token from the command line

## You can see files in Windows via \\wsl.localhost\Ubuntu-24.04