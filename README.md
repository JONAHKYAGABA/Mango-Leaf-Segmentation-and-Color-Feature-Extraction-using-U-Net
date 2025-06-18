# Mango-Leaf-Segmentation-and-Color-Feature-Extraction-using-U-Net

This project implements a full pipeline for mango leaf image segmentation using a custom U-Net architecture. It uses the Roboflow dataset interface to download YOLO-formatted training data, processes labels into masks, trains a U-Net model on image segmentation, and extracts HSV-based color features from the segmented regions.

🚀 Features
✅ Automatic dataset download via Roboflow

✅ Converts YOLO-style bounding boxes to binary masks

✅ Custom U-Net model for binary image segmentation

✅ Training pipeline with Dice, IoU, Precision, Recall evaluation metrics

✅ Segmentation of test images

✅ HSV color feature extraction (mean & std per channel)

✅ Saves features to a CSV file for downstream analysis
