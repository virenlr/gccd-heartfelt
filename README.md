# gccd-heartfelt #
This repository hosts the code used at the demo for Google Cloud's Professional Machine Learning Engineer examination session at Google Cloud Community Days - India (Jan 22-23, 2021).

> Note: I welcome you to show me the improvements you make to my model/dataset! You can also show me any cool applications you build with my code as a starting point. Please open a Github Issue and upload your files. I will be happy to leave my comments. But please don't ask me to fix bugs!

### Getting Started

Please download the dataset file titled _heartfelt_dataset.csv_ (don't rename it) as well as the Jupyter notebook corresponding to your environment. Use _Heartfelt (GCP)_ when running on Google Cloud's AI Platform and _Heartfelt (Colab)_ otherwise. You can run each cell one at a time and play around with the code.

If you're feeling up to it, there are homework exercises at the end you can do. I would love to see what you make!

### Setting up on Colab

Open Colab and upload the notebook. Without changing the name, upload the dataset to the /content folder (it will be opened by default when you click the Files tab at the left of the screen). You can run the cells one by one and play around with the code. Colab is 100% free.

### Setting up on GCP

Set up your GCP account as required; you may need to use your credit card to avail of the free $300 trial. Go to the Notebooks section under AI Platform (not Unified AI Platform). Click New Instance and select TensorFlow 2.3 Enterprise > Without GPUs. You can change the instance name (or leave it as it is) and click Create. It will take about 10 minutes before the _Open Jupyter Lab_ option becomes available. When it does, click the button, and Jupyter Lab will open in a new tab.

You can use the Files pane at the left of the screen to upload the Jupyter notebook and dataset file (without changing the name). Double click the notebook to open it. You can run the cells one by one and play around with the code. You may need to go to the Jobs and Models sections of the AI Platform to enable these APIs.

**Be sure to delete your instance when you're done. Otherwise, you will burn right through your $300 credit!** There are still some minor costs associated with your instance when it is turned off, so to be entirely sure that you aren't losing money, please delete your instance. You will also need to delete the model you deploy to AI Platform Models after you finish playing with it.
