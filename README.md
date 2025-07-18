##🧵 Pattern Sense: Classifying Fabric Patterns Using Deep Learning

## 📁 Project Structure

```plaintext
project_directory/
├── app.py
├── Data.py
├── TrainCNN.py
├── requirements.txt
├── fabric_pattern_model.h5 # generated after training
├── templates/
│ ├── index.html
│ └── result.html
```


---

## ⚙️ Setup Instructions

### 1. Clone or Download the Project

Download or clone this repository and navigate into it:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2.Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
# OR
source venv/bin/activate  # For macOS/Linux
```

### 3.Install Dependencies

```bash
pip install -r requirements.txt
```
---

## 📊 Dataset Preparation

Ensure your dataset is located at the following path:

D:\projectfabric\Fabric\Clothing Pattern Classification Dataset (MD-Fashion-2)_Samples


### Or update the `data_dir` path in `Data.py` to reflect your actual dataset location.

---

## 🧠 Model Training

### 1. Run the data preprocessing script:

```bash
python Data.py
```

### 2.Train the CNN model and save it:
```bash
python TrainCNN.py
```
### This will generate a fabric_pattern_model.h5 file.

⚠️ Note: Make sure variables like X_train, y_train, etc., are correctly defined or imported in TrainCNN.py.


---

