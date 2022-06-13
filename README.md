# Almari Cloud Deployement
The source code and documentation of Almari's cloud deployment on Google Cloud Console using Cloud Functions.

## Service Architecture


## How to Deploy
1. Clone this repository the Cloud Deployment folder.
2. Create a storage bucket on Google Cloud Storage and upload [my_model3.h5] and [my_model.h5] into your bucket.
3. Create a Cloud Function for [clothing-detection] and choose 2 GB allocated memory, trigger (HTTP trigger) and runtime (python 3.7).
4. Set main.py and requirements.txt files by copying the code from [clothing-detection.py] file. 
5. Set 'handler' for the function to execute and click create.
6. Repeat step 3 for the [color-detection.py].