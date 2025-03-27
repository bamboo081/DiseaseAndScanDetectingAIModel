# DiseaseAndScanDetectingAIModel
Detects CT scans, MRI scans, and X-ray scans while also listing the problem in each scan. Trained on a few diseases in each scan but not too smart, still being developed. Only .h5 file for the model, code is being refined.
When using model to improve ones own model, please credit bamboo081 on Github. 
Instructions: 
Download the .zip file and use Winrar(or windows unzipper tool) to unzip it, then import it to your project under a subdirectory "models" and copy both models in the .zip file to this subfolder in your project. After doing so, call upon the .h5 files to test them, then refine them or change them to your needs.
This project checks scans for type of scan as well as type of disease and gives a top 3 probability for each, and picks the most probable scan. So far it detects MRI, CT, and X-ray scans. It also checks for certain disease types in these scans as well. For X-ray scans, it gives result "X-ray" and picks either normal x-ray, COVID, fracture, or pneumonia. For CT scans, it gives either normal ct, cyst, stone, or tumor. For MRI, it gives either normal MRI, glioma, meningioma, or pituitary. 
Note that the model is not 100 percent accurate, and leans towards certain options at times. Model is being trained and refined and updated weekly.
