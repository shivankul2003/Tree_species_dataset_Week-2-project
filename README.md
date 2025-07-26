
# 🌳 Tree Intelligence Assistant

The **Tree Intelligence Assistant** is an AI-powered platform designed to help **students, researchers, and nature lovers** identify, study, and explore tree species using a combination of **image recognition, location-based insights, and tree attributes**.

---

## ✨ Key Features
- **🌲 Location-based Tree Suggestions** – Discover the tree species that thrive in a particular location.  
- **📍 Tree-to-Location Search** – Find the regions or habitats where a specific tree species grows.  
- **📷 Image-based Identification** – Upload an image to instantly identify the tree species using a trained CNN model.  
- **📊 Dataset Overview** – Get detailed information about the dataset used for training and validation.  
- **🗂️ Tree Metadata Access** – Explore attributes such as tree height, leaf structure, and taxonomy.  
- **🖼️ Curated Image Collection** – A well-organized dataset of tree images to ensure accurate classification.  

---

## 🧠 Technology & Algorithms
- **🔍 Recommendation Engine** – Suggests relevant tree species based on the user’s location and preferences.  
- **🧠 Convolutional Neural Networks (CNN)** – For precise image classification and species detection.  
- **⚙ Data Preprocessing** – Includes feature scaling, label encoding, and image augmentation for optimal results.  

---

## 🚀 How to Use
1. **Train the Tree Recommender:**  
   Open and run:  
   ```bash
   5M_trees.ipynb
   ```  
   This will create:
   - `tree_data.pkl`  
   - `scaler.joblib`  
   - `nn_model.joblib`

2. **Train the Image Classifier:**  
   Open and run:  
   ```bash
   tree_CNN.ipynb
   ```  
   The trained CNN model will be saved as:  
   - `basic_cnn_tree_species.h5`

3. **Launch the Web Application:**  
   Use Streamlit to start the integrated interface:  
   ```bash
   streamlit run streamlit_integrated.py
   ```
---

## 🔧 Tools & Libraries
- **Core Libraries:** TensorFlow, Keras, Scikit-learn, Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Web Framework:** Streamlit  
- **Environment:** Python 3.8+ and Jupyter Notebook

---

