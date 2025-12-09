# Masked-Image-Modelling-Based-Self-Supervised-Pre-training-for-Remote-Sensing-Object-Detection
This repository contains the code and files for running my implementation of Object-Centric Masked Image Modelling (OC-MIM) for remote sensing object detection.
The project includes the trained models, test images, and scripts needed to run inference or reproduce the results.

📁 What’s Included
models/           Pretrained weights for the OC-MIM model and detection head
testimages/       Example remote sensing images for testing
code/             All source code (training, inference, utilities, etc.)
requirements.txt  Python dependencies
run.bat           Quick-run script for Windows

🔧 Setup

Make sure you have Python 3.8+ installed.

Install the required Python packages:

pip install -r requirements.txt


(Optional) Create and use a virtual environment if you prefer keeping dependencies isolated.

▶️ How to Run

If you're on Windows, you can simply double-click:

run.bat


This will automatically load the model from the models/ folder and run inference on the images inside testimages/.

If you prefer running it manually:

python code/main.py --model models/<your_model_file>.pth --input testimages/


Modify paths if needed depending on your folder structure.

🧪 Testing

The testimages/ folder contains a few sample remote sensing images you can use to verify everything is working.
Outputs (predictions, visualized detections, logs) will be saved in the directory specified inside the script—usually something like:

results/

📌 Notes

Make sure that your model file names inside the models/ folder match what the code expects.

If you want to use your own images, just place them inside the testimages/ folder or point the script to a new directory.

If you run into import errors, double-check that all dependencies were installed correctly.

👍 Contributions

If you'd like to improve or extend this project, feel free to open an issue or submit a pull request.

📬 Contact

For questions or help, you can reach me at:

Sathwik Chinthakindhi
Email: sathwik.chinthakindhi26@gmail.com
