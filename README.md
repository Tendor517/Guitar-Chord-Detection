# Guitar-Chord-Detection
It's an manually trained simple model.

1. Run collect_data.py to train and collect the finger position data into the chord_dataset.csv file, which record an 10 second video with 30 frames/second and uses mediapipe,cv2 and numpy
   to collect the finger positions for that particular chord, try tilting the neck of guitar left/right/top/bottom angle wise for more robust data collection.
2. Run the train_model.py to train it 20/80 test/train split using these libraries: tensorflow, numpy, pandas and scikit-learn.
3. Run the live_cam.py file to detect the chord names live on the camera as you play the chords on guitar which were traied before.

