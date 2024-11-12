# Traffic Sign Detection and Warning System

This project is a real-time Traffic Sign Detection and Warning System built using Streamlit, OpenCV, and YOLO (You Only Look Once) models from the `ultralytics` library. The application captures live video feed from the camera, detects traffic signs, and provides real-time feedback to help users recognize traffic signs effectively.

## Features
- **Real-time Traffic Sign Detection**: Uses YOLO models to detect traffic signs in live video.
- **Streamlit Interface**: Simple and interactive web interface using Streamlit.
- **Easy to Use**: Designed for real-time detection without uploading images, capturing video directly from the user's camera.

## Requirements

- Python 3.7+
- OpenCV
- Streamlit
- Ultralytics (for YOLO models)

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/SaiGawand12/TRAFIC-SIGN-DETECTION-AND-WARNING-SYSTEM.git
   cd TRAFIC-SIGN-DETECTION-AND-WARNING-SYSTEM
   ```

2. **Set Up a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv env
   # Activate the virtual environment
   # On Windows
   .\env\Scripts\activate
   # On macOS/Linux
   source env/bin/activate
   ```

3. **Install Dependencies**

   Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is not provided, install dependencies manually:

   ```bash
   pip install streamlit opencv-python-headless ultralytics
   ```

## Usage

1. **Run the Application**

   Start the Streamlit app by running the following command:

   ```bash
   streamlit run app.py
   ```

2. **Using the Application**

   - Once the app opens in your browser, it will access your camera.
   - The system will start detecting traffic signs in real-time and display them in the Streamlit interface.
   - Press the "Stop Camera" button to end the video capture.

## Project Structure

- `app.py`: Main Streamlit application file.
- `real_time.py`: Contains the traffic sign detection functions utilizing YOLO.
- `requirements.txt`: List of required Python packages.
- Additional files and directories may include detection model files, configuration, and helper scripts.

## Troubleshooting

- **ModuleNotFoundError**: If you encounter an error saying `No module named 'ultralytics'`, install it by running `pip install ultralytics`.
- **Camera Access Issues**: Ensure your browser and Streamlit have permission to access the camera.

## Acknowledgments

- **Ultralytics**: For the YOLO models used in real-time detection.
- **OpenCV and Streamlit**: For enabling real-time computer vision and a user-friendly web interface.

## License

This project is licensed under the MIT License.

---
