# EEG Based Cognitive State Classification

- A Undergrad project focused on detecting students' cognitive states while watching educational videos, using EEG signals as the main input.
- [Link to Kaggle Project](https://www.kaggle.com/code/cayoonhee/confused-student-eeg-project)

### Abstract

This report evaluates EEG brainwave data collected from college students watching
STEM-related Massive Open Online Courses (MOOC) videos to classify whether a
student was confused during a session. The dataset includes temporal EEG signals,
attention and meditation scores, and demographic information, enabling us to test
various machine learning and deep learning algorithms for binary classification.
Initially, we preprocessed the data by normalizing features and experimented with
an aggregated approach by averaging signals across video sessions to simplify the
dataset for traditional models like SVM and KNN. Later, we explored sequential
models, such as LSTMs and CNNs, leveraging their ability to capture temporal
and spatial patterns in the raw EEG data. The results demonstrated the strengths
of deep learning models, with the KNN and SVM achieving a test accuracy of
99%, the RNN achieving 100%, the CNN achieving 97% and the LSTM achieving
96%. Our findings highlight the importance of retaining temporal information in
EEG data and optimizing model hyperparameters to balance generalization and
computational efficiency.

Co-writer: [Hassan Alawie](https://www.linkedin.com/in/hassanalawie/)
