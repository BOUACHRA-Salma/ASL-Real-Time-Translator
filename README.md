# ASL-Real-Time-Translator
Real-time American Sign Language detection using MediaPipe and TensorFlow
# 🤟 Real-Time American Sign Language (ASL) Recognition


Welcome to this real-time American Sign Language (ASL) detection and translation project. This model uses landmark extraction via **MediaPipe** combined with a neural network developed using **TensorFlow/Keras**.

---

## ⚙️ Environment and Required Versions

To ensure the code runs smoothly and to avoid compatibility errors when loading the pre-trained model, please make sure to use the following versions:

- **Python** >= 3.9
- **TensorFlow == 2.15.0** ⚠️ *(Very important for correctly reading the `.keras` file)*
- **MediaPipe**
- **OpenCV** (`opencv-python`)
- **Pandas**, **Numpy**, **Scikit-learn**, **Matplotlib**, **Seaborn**

> **💡 Note:** The default versions installed on cloud environments like Google Colab may differ from the required ones and cause errors during model importation.

---

## 🚀 Testing the Project

### Local Execution (Jupyter Notebook)

To test the live translation using your camera:
1. Clone this repository or download the files locally.
2. Open the `ASL.ipynb` file using Jupyter Notebook, Jupyter Lab, or VS Code.
3. Scroll down to the last cell named **"Déploiement"** (Deployment) or run the entire notebook.
4. Run the cell: a video window will open to analyze your hand gestures.
5. Press the `q` key on your keyboard to cleanly close the camera.

> **⚠️ Warning regarding Google Colab:**
> Opening the webcam via the OpenCV library (`cv2.VideoCapture`) does not work natively on Google Colab. **Local execution is strictly required** to run the real-time deployment cell.


https://github.com/user-attachments/assets/a02d2053-81b2-478e-a16a-fb532f153e22






---

*Thank you for your evaluation and interest in this project!*
