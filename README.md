
# 🧠 Visual AI in Healthcare with FiftyOne

Welcome to the **Visual AI in Healthcare** workshop!  
This hands-on experience is designed to help you explore how data-centric tools like [FiftyOne](https://voxel51.com/fiftyone/) empower developers, researchers, and healthcare professionals to load, explore, curate, and visualize medical imaging datasets for computer vision tasks.

You’ll work across real-world datasets (e.g., ARCADE, DeepLesion, VISTA-3D, MedSAM, MedGemma) and tackle challenges like segmentation, classification, and vision-language understanding — all without needing extensive prior ML knowledge.

---

## 📅 Workshop Agenda

| Step | Notebook | Description |
|------|----------|-------------|
| 1️⃣ | `01_load_arcade_dataset.ipynb` | Load and visualize the ARCADE dataset using FiftyOne. Learn how to navigate metadata, preview modalities, and understand label formats. |
| 2️⃣ | `02_load_deeplesion_balanced.ipynb` | Work with a curated DeepLesion subset. Understand data balance, filtering, and statistics using FiftyOne’s interactive UI. |
| 3️⃣ | `03_vfms_analysis_arcade.ipynb` | Dive into embeddings and similarity search. Use VFM (visual foundation models) to analyze and organize ARCADE images semantically. |
| 4️⃣ | `04_finetune_yolo8_stenosis.ipynb` | Fine-tune YOLOv8 on a medical stenosis dataset. Export predictions, analyze performance, and learn model-centric strategies with FiftyOne. |
| 5️⃣ | `05_medsam2_ct_scan.ipynb` | Use MedSAM2 for segmenting CT scans. Integrate predictions into FiftyOne for inspection and post-processing. |
| 6️⃣ | `06_nvidia_vista_segmentation.ipynb` | Visualize VISTA multi-organ segmentation results. Explore segmentation masks across slices and volumes with FiftyOne. |
| 7️⃣ | `07_medgemma_vqa.ipynb` | Run vision-language tasks with MedGemma. Answer clinical questions based on radiology images and validate results using FiftyOne. |

---

## 🎯 Learning Objectives

By the end of this workshop, you will:

- Understand the fundamentals of data-centric AI in healthcare
- Load, visualize, and manipulate DICOM and medical imaging datasets
- Use embedding-based search for semantic exploration of visual data
- Evaluate model performance, errors, and quality via visual tools
- Apply foundation models like MedSAM2 and MedGemma with ease
- Learn to integrate AI outputs back into your medical imaging pipeline

---

## 🔧 Workshop Setup

To run the notebooks locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/paularamo/fiftyone-workshop-healthcare.git
cd fiftyone-workshop-healthcare
```

### 2. (Optional) Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install required packages
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Launch the notebooks
```bash
jupyter notebook
```

**Note:**  
- You may need API access for some models or datasets (refer to notebook instructions).
- GPU acceleration is recommended for faster model inference. And mandatory for the MedGemma notebook.

---

## 🚀 Run in Colab

WIP - Once this is ready, you can run selected notebooks directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-org/visual-ai-healthcare)

Make sure to:
- Enable GPU under Runtime > Change runtime type
- Upload required files or connect to Google Drive as needed

---

## 🐳 Docker-Compose Setup

WIP - For a containerized setup, use Docker Compose.

---

## 🧪 Datasets Used

- **ARCADE**: A curated dataset for pediatric imaging
- **DeepLesion**: A large-scale lesion dataset from NIH
- **Stenosis subset**: For YOLOv8 fine-tuning
- **MedSAM2**: Medical version of the Segment Anything model
- **NVIDIA VISTA 3D**: Multi-organ CT scan dataset
- **MedGemma**: Vision-language model trained on radiology images and reports

---

## 🙋 Support & Contribution

If you have questions or suggestions:

- 📬 Open an issue or pull request  
- 💬 Join the [FiftyOne Discord Community](https://voxel51.com/community)  
- ⭐ Star [FiftyOne on GitHub](https://github.com/voxel51/fiftyone)  

---

## 👩‍⚕️ Built With Purpose

This workshop was designed to **democratize access to Visual AI in healthcare** — making state-of-the-art tools accessible for doctors, engineers, and researchers alike.
