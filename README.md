# Text Mining for Online Toxicity: Insights from Classification and Topic Modeling

## 1. System Requirements
- **Language**: Python
- **Platform**: Google Colab (recommended) or Local Environment
- **Libraries**: Install via `requirements.txt` (for local execution only)

## 2. Project Structure
```
├── notebooks/
│   ├── 01_overview_and_preprocessing.ipynb  # Data loading and preprocessing
│   ├── classification/                      # Notebooks for classification tasks
│   │   ├── 02_representation.ipynb          # Feature representation (TF-IDF, embeddings)
│   │   ├── 03_train.ipynb                    # Model training (Logistic Regression, DistilBERT)
│   │   ├── 04_predict.ipynb                  # Model predictions
│   │   ├── 05_evaluate.ipynb                 # Model evaluation and comparison
│   │
│   ├── topic_modeling/                       # Notebooks for topic modeling tasks
│   │   ├── 02_representation.ipynb          # Text representation for LDA
│   │   ├── 03_topic_modeling.ipynb          # LDA model training
│   │   ├── 04_topic_model_analysis.ipynb    # Analysis of topics on the global dataset
│   │   ├── 05_toxic_topic_model_analysis.ipynb # Topic analysis for toxic comments
│
├── text_mining_presentation.pdf  # Slides for the project presentation
├── text_mining_report.pdf        # The project paper detailing the methodology and results
├── requirements.txt              # List of dependencies (for local usage only)
```
## 3. Data, Models, and Outputs
The following directories are stored on **Google Drive** and not included in this repository:
- **Data** (`data/`): Raw and processed datasets.
- **Models** (`models/`): Trained models for classification and topic modeling.
- **Outputs** (`outputs/`): Results and evaluation outputs.

📂 You can access them here: [Google Drive Link](https://drive.google.com/drive/folders/1VH4K_5kkqcp9m_Kdi2XjrbTkCf8OYlzo?usp=drive_link)

## 4. How to Run
- Open the desired notebook on **Google Colab**.
- Execute all cells sequentially.
- Required data and dependencies are loaded within the notebooks using pre-defined Google Drive links.

## 5. Local Usage (Optional)
- Download the project folder.
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- **Note**: The `requirements.txt` file was generated directly from Google Colab.
  It may include extra dependencies not strictly required to run the project.
- Run the notebooks manually.

## 6. Notes
- The notebooks are **numbered in a logical order** to guide execution:
  - Start with `01_overview_and_preprocessing.ipynb` for data preparation.
  - Move to the **classification** or **topic_modeling** folders depending on the task.
- Notebooks are **independent**; each loads the necessary data and checkpoints using pre-defined Google Drive links.
- An **internet connection** is required for data download.

---


