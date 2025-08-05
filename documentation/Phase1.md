
# Project Phase 1

Object detection phase 1 - training a model to detect objects undamaged residential buildings and undamaged commercial buildings

## Key steps

1. Train model to an acceptable level of accuracy mAP > 0.7
2. Use trained model to analyse all remaining images
3. From roboflow download all annotated tiles used for the model training
4. Optional: filter these tiles from the list of tiles for analysis
5. From analyzed images, get the number of commercial buildings per image
6. Select the tile names that have multiple images and then upload them to Roboflow
7. Annotate images in roboflow manualy
8. Use extended dataset with a better class balance in the model training
9. Repeat steps 1. to 8

## TODOs

- [ ]: Check the number of background imaged in Roboglow vs number images detected by YOLO training algorithm

