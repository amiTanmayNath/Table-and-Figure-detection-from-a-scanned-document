# Table-and-Figure-detection-from-a-scanned-document


# Project Workflow Instructions

## Step 1: Model Training
- Run the notebook `trident_on_pubnet_fine_tune.ipynb` to train the model.
- The script utilizes the data augmentation methods specified in the project report.
- Once training is complete, the model weights will be saved to the specified output directory.

## Step 2: Model Utilization
- Open the notebook `Final_presentation_demo.ipynb`.
- Load the trained model weights by specifying the correct file path in the notebook.
- Ensure the weights generated from the previous step are used for consistent results.

## Step 3: Document Upload and Path Configuration
- Upload the document(s) you want to process.
- In the `Final_presentation_demo.ipynb` notebook, update the file path(s) to point to the uploaded document(s).

## Notes
- The notebooks must be executed in the given order to ensure proper functionality.
- Refer to the project report for additional details on data augmentation and the training process.

