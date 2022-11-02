# Detectron2-LAT-Detection
Simulates LAT sources (as .jpeg files), then trains a Detectron2 Mask R-CNN on them. 

Use scripts in Data_Generator_VOC to generate data and corresponding annotations in Pascal VOC format. Use scripts in Data_Generator_COCO to 
generate data and corresponding annotations in COCO format. Then use Mask R-CNN training script to load datasets, load model architectures, and train.
