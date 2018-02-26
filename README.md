# TuriCreate-Easy-Scripts
Easy-to-use scripts to create a CoreML model file

## How to use

### Gather data
```
npm install
node imagenet-downloader.js your_imagenet_category_url your_output_folder
```

### Train model
Once you've got your training data downloaded, you can run the script like so:
```
python train-model.py
```

This will output a file called Classifier.mlmodel 
