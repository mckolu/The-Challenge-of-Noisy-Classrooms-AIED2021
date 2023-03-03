<h1>Detecting Speakers in Noisy Environments</h1>

<p>This is the repository for our research paper accepted at the International Conference on Artificial Intelligence in Education (AIED'21)</h1>
 
<p><b>Paper Link: </b><a href="http://learndialogue.org/pdf/LearnDialogue-Ma-AIED-2021.pdf">The Challenge of Noisy Classrooms: Speaker Detection During Elementary Students’ Collaborative Dialogue</a></p>

<h3>Introduction</h3>
<a href="https://github.com/mckolu/The-Challenge-of-Noisy-Classrooms-AIED2021/blob/main/Images/model.jpg"><img align="right" width="430" height="auto" src="https://github.com/mckolu/The-Challenge-of-Noisy-Classrooms-AIED2021/blob/main/Images/model.jpg"></a>

<p>Adaptive and intelligent collaborative learning support systems are effective for supporting learning, yet, this potential has not yet been realized within noisy classroom environments, where automated speech recognition (ASR) is very difficult. A key challenge is to differentiate each learner’s speech from the background noise, which includes the teachers’ speech as well as other groups’ speech. In this paper, we explore a multimodal method to identify speakers by using visual and acoustic features from ten video recordings of children pairs collaborating in an elementary school classroom. The results indicate that the visual modality was better for identifying the speaker when in-group speech was detected, while the acoustic modality was better for differentiating in-group speech from background speech. Our analysis also revealed that recurrent neural network (RNN)-based models outperformed convolutional neural network (CNN)-based models with higher speaker detection F-1 scores. This work represents a critical step toward the classroom deployment of intelligent systems that support collaborative learning. </p>
<!-- <h3>Citation</h3> -->
<!-- <pre></pre> -->

<h2> Prerequisites </h2>
<p>Basics </p>
<pre>
Python3 
CPU or NVIDIA GPU + CUDA CuDNN
</pre>
<p>Prerequisites for feature extraction</p>
<pre>
opencv 3.4.3
librosa 0.8.0
</pre>
<p>Prerequisites for model training</p>
<pre>
tensowflow-gpu 2.1.0
keras 2.3.1

</pre>

<h2>Structure (Keep Updating...)</h2>
<pre>
├───Feature_Extraction
│   ├───detect_facial_blob
│   │   └───model_data
│   │   └───detect_facial_blob.py
│   └───real_time_feature_extraction_with_webcam
│   │   └───model_data
│   │   └───detect_facial_blob.py
│   │   └───tract_motion_with_webcam_input.py
│   └───compute_dense_optical_flow.py
│   └───compute_mel_spectrogram.py
│   └───compute_sparse_optical_flow.py
└───Model
</pre>

<!-- <h2>Other Supplementary Materials</h2>
<p>Please refer to the image files in './Images/' path.</p> -->
<!-- <p>1. Annotation Example</p> -->
<!-- <p>2. Feature Extraction Process</p> -->
