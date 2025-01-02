# ESP32-CAM-Grand-Prize

1. How to Run
 Install dependencies:
    pip install numpy opencv-python tensorflow
    
 Create the following directories:
    ./ct_images - Place CT images here.
    ./models - Add the segmentation_model.tflite here.
    ./output - Output files will be saved here.
    
 Run the script:
    python esp32_cam_pipeline.py
    
2. Outputs
  The script will generate the following files in the output directory:
    segmented_image.png - Flattened segmented papyrus with a scale bar.
    ink_detected.png - Ink-detected regions with a scale bar.
