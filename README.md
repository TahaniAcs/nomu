# nomu
Nomu: Smart Platform for Community Agriculture and Afforestation
🌿 Nomu (نمو): Smart Agricultural Platform

Nomu is an AI-driven ecosystem designed to revolutionize the Saudi agricultural sector by bridging the gap between advanced deep learning and community-driven afforestation.  
🚀 Key Features

    AI Harvest Analytics: Utilizing a custom-trained YOLOv8 model to detect, count, and estimate fruit yield with high precision.  

    Logistics Optimization: A unified platform to coordinate volunteers and farmers for efficient harvest management.  

    Future Vision: Strategic framework for early disaster and pest prediction using satellite data integration.  

🛠 Technical Infrastructure

    Core Model: YOLOv8 Small architecture.  

    Computational Power: Training executed on the advanced NVIDIA H200 GPU.  

    Dataset: Specialized Figs & Olives dataset sourced and engineered via Roboflow.  

    Optimization Techniques:

        Transfer Learning: Leveraging pre-trained weights for superior feature extraction.  

        Early Stopping: Automatically terminated at Epoch 42, reducing training time by 50% while preventing overfitting.  

📂 Project Structure

Following a professional directory hierarchy optimized for cloud workflows:  

    Config/: YAML configuration files defining class paths.  

    Models/: Final weights for the best-performing models (e.g., best.pt).  

    Notebooks/: Colab scripts for dataset integration and model training.  

    Results/: Performance metrics, including logs and confusion matrices.  

📊 Performance Metrics

    Overall mAP50: 88.6%.  

    Peak Class Accuracy (Olives): 90.7%.  

    Inference Speed: 0.6ms per image.  

💻 Installation & Usage

To run the project locally, ensure you have the required dependencies and use the py launcher:

py -m pip install -r requirements.txt

**Run the Platform:**
    Start the main application (which integrates the UI with the AI backend):
    ```bash
    py app.py
    ```
