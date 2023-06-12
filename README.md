# Text-detect-from-CNIC
Evaluation Task - Text Detector

Task: Text Detection on ID Card Images

Description: In this task your goal is to train a deep learning model to detect the text in ID cards. And compare its performance with a pre-trained EAST model.

Steps:

Download the any dataset available on internet or create your custom dataset. And split it into training and testing sets.

Pre-process the images by resizing them to a fixed size and normalizing their pixel values, if required.

Annotate the training set using a tool like LabelImg or via to draw bounding boxes around the text regions, if required.

Train a deep learning model on the annotated dataset to detect text.

Evaluate* the trained model on the testing set by computing the precision, recall, and F1-score. Remember that the testing dataset will be should be only id cards images.

Compare your model's performance with that of an existing state-of-the-art text detection model such as EAST or CRAFT on the same testing set.

* Text detection is a different task from binary classification, so the evaluation metrics used for binary classification, such as precision, recall, and F1-score, may not be applicable to text detection. Instead, text detection evaluation metrics are typically based on the bounding boxes that surround the detected text.

The common evaluation metrics for text detection include:

Intersection over Union (IoU): This metric measures the overlap between the predicted bounding boxes and the ground truth bounding boxes. A high IoU score indicates a good match between the predicted and ground truth bounding boxes.

Precision: This metric measures the proportion of predicted text regions that are true positives. A high precision indicates that most of the predicted text regions are true text regions.

Recall: This metric measures the proportion of true text regions that are detected by the model. A high recall indicates that most of the true text regions are detected.

F1-score: This metric is the harmonic mean of precision and recall. It provides a single score that balances the trade-off between precision and recall.

So, while precision, recall, and F1-score may not be directly applicable to text detection, they can be adapted to evaluate the performance of text detectors using the bounding box annotations.

Training Dataset: There are several sources where you can find ID card datasets for various countries. Here are a few examples:

COCO-Text dataset: This dataset includes images of various documents, including ID cards, with corresponding annotations. You can find more information and download the dataset here: https://vision.cornell.edu/se3/coco-text-2/

Passport and ID Card dataset: This dataset includes images of passports and ID cards from various countries with corresponding annotations. You can find more information and download the dataset here: https://zenodo.org/record/3247319#.YbbhdqgzbIU

SynthText in the Wild dataset: This dataset includes synthetic images of text in natural scenes, including ID cards, with corresponding annotations. You can find more information and download the dataset here: https://www.robots.ox.ac.uk/~vgg/data/scenetext/

Estimated time: This task should take approximately 3 to 4 hours to complete.


Note: This is a challenging task, and you may need to spend additional time tuning the hyperparameters and adjusting the model architecture to achieve the best performance. Good luck!
