# edge-detection
to run orgininal edge detection download hed_pretrained_bsds.caffemodel and deploy.prototxt and put them in a 
folder called hed_model
then run 
I would have uploaded the model but ot os too large for github to be happy

$ OriginaledgeDetector.py --edge-detector hed_model

in the command window

should run much faster with gpu use but I cannot figure out how to download the nvidia gpu drivers
