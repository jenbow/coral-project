# starting base image
FROM --platform linux/x86_64/arm64 python:3.6.13

# getting github package
RUN git clone https://github.com/jenbow/Mask_RCNN.git

# changing to Mask_RCNN directory
WORKDIR /Mask_RCNN

RUN python -m pip install -r requirements.txt
RUN python setup.py install 
