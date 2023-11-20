# Deepfake-Detection

Overview

This repository contains code for a deepfake detection project. The project focuses on detecting manipulated videos, referred to as deepfakes, by leveraging deep learning techniques and exploratory data analysis (EDA).

What is DeepFake?

DeepFake is a term derived from 'Deep Learning' and 'Fake.' It describes the process of replacing individuals within images or videos using sophisticated technologies like Deep Artificial Neural Networks [1]. The emergence of deepfakes poses a significant threat to various industries, including film and news agencies. To combat this, major companies like Google invest heavily in developing tools and datasets to counter the spread of deepfakes [2].

Project Goals

Detect and classify videos as real or deepfakes.

Utilize exploratory data analysis techniques to understand and process the dataset effectively.

Employ OpenCV Haar Cascade resources to extract facial features and objects from videos.

Dataset Description

The dataset comprises .mp4 video files divided into compressed sets of approximately 10GB each. Accompanying these video sets are metadata.json files containing essential information such as filenames, labels (REAL/FAKE), original video references, and split details.

Files Included

train_sample_videos.zip: A sample set of training videos along with metadata.json.

test_videos.zip: A small validation set of videos for public use.

Columns in Metadata

filename: Video file names.

label: Indicates whether the video is REAL or FAKE.

original: For FAKE videos, references the original video.

split: Always marked as "train."

Prediction Task

The primary objective is to predict the probability that a given video is a deepfake. The training data labels videos as "REAL" or "FAKE" in the label column. 

Repository Structure

/data: Contains the provided video datasets and metadata.

/notebooks: Jupyter notebooks detailing the data exploration, model development, and analysis.

/scripts: Code scripts used for data processing, model training, and evaluation.

/models: Saved models or model checkpoints.

/results: Output and result files generated during the project.
