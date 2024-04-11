# Satellite Image Dehazing

This project implements an image dehazing technique using the AOD-Net architecture.

## Folder Structure

- **`readme.md`**: Instructions for setting up and running the project.
- **`requirements.txt`**: Contains all necessary Python libraries.
- **`dehazing-code.ipynb`**: Jupyter notebook with the full dehazing code.
- **`dehazing.py`**: Python code to run the dehazing UI on Windows OS.
- **`run_cvip_ui_picker.bat`**: Batch file to launch the dehazing UI on Windows.
- **`run.py`**: Python script to run the UI on any operating system.
- **`test_dataset/`**: Folder containing hazy image test data.
- **`AOD_Net_reg.h5`**: Saved model in Hierarchical Data Format (HDF).

## Getting Started

Follow these instructions to set up your environment to run the project.

### Prerequisites

Ensure you have Python 3.6 or higher installed on your machine. Install all the required dependencies with one of the following methods:

#### Using `requirements.txt`

```bash
pip install -r requirements.txt
```

Alternatively, you can install the dependencies directly using:
```bash
pip install opencv-python numpy tensorflow matplotlib scikit-image keras tkinter PIL
```

### Running the Dehazing App On Windows:
1. Double-click the run_cvip_ui_picker.bat file to start the application.
2. Wait for the app to open, and then upload an image from the directory using the UI.
   
On macOS or Linux:
1. Open a terminal.

2. Execute the following command:
 ```bash
python run.py
```

3. To dehaze a different image, change the image path in the img variable inside run.py. For example:
   img = cv2.imread('file_path')

**Note**: Keep the command prompt open while the app is running.
