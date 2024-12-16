# **Image Background Removal Project**
This project demonstrates how to remove the background from an image using Python. The solution uses the `rembg` library and `Pillow` (PIL) to process images and save the results with transparent backgrounds.

*Features*: 
- Automatically removes the background from any image.
- Simple and easy-to-use Python script.
- Saves the output image with a transparent background.

*Requirements*: 
Ensure the following are installed on your system:
- Python 3.6 or higher
- pip (Python package installer)
  
Required Python libraries:
- rembg
- Pillow
- onnxruntime (required by rembg)
  

*Project Structure*
Image-Background-Removal-Project/
├── input_image.jpg          # Input image (replace with your image)
├── output_image.png         # Output image (background removed)
├── background_removal.py    # Python script for background removal
└── README.md                # Project documentation

*Usage*: 
1. *Place the input image*:
    Save the image you want to process in the project folder and rename it to `input_image.jpg`. 
    Or update the `input_path` in the script to point to your image file.

2. **Run the Python script**:
   Open a terminal, navigate to the project folder, and run:
   ```bash
   python background_removal.py     --> command to get output image

3. **Check the output**:
   - The script will save the processed image as `output_image.png` in the project folder.
   - This image will have the background removed.
-----------------------------------------------------------

 *Running in Jupyter Notebook*: 
Alternatively, you can adapt the script for use in a Jupyter Notebook. Paste the following background_removal code into a notebook cell and run it:
