
In this project, we attempt to measure heart rates in humansusingcamera-basedremotephotoplethysmography (RPPG) methods, named after traditional PPG. The fundamental idea is based on capturing minute changes in skin color during a cardiac cycle of the human body, involving the inﬂow and outﬂow of blood from the heart to other body parts. We have compared the performance of different methods of Blind Source Separation and face detection which form an integral part in accurately calculating the heart rate.


The methodology consists of 2 main steps. Firstly, the videos in the dataset is run through a face detection model to get the region of interest for heart rate calculation. This is followed by dividing the detected ROI into RBG channels and applying Source Separation(PCA/ICA) algorithm toobtainthesourcesignals. Sourcesignalsareconvertedto frequency domain for ﬁltering and peak detection to obtain heart rate estimates
