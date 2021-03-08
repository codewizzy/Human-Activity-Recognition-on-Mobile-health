# Human-Activity-Recognition-on-Mobile-health

### Description
The MHEALTH (Mobile HEALTH) dataset comprises body motion and vital signs recordings for ten volunteers of diverse profile while performing several physical activities.
Sensors placed on the subject's chest, right wrist and left ankle are used to measure the motion experienced by diverse body parts, namely, acceleration, rate of turn and magnetic field orientation. 
The sensor positioned on the chest also provides 2-lead ECG measurements, which can be potentially used for basic heart monitoring, checking for various arrhythmias or looking at the effects of exercise on the ECG.

### ACTIVITY SET
The activity set is listed in the following:

* L1: Standing still (1 min)
* L2: Sitting and relaxing (1 min)
* L3: Lying down (1 min)
* L4: Walking (1 min)
* L5: Climbing stairs (1 min)
* L6: Waist bends forward (20x)
* L7: Frontal elevation of arms (20x)
* L8: Knees bending (crouching) (20x)
* L9: Cycling (1 min)
* L10: Jogging (1 min)
* L11: Running (1 min)
* L12: Jump front & back (20x)

We’ll use accelerometer data, collected from multiple users, to build a Bidirectional LSTM model and try to classify the user activity. You can deploy/reuse the trained model on any device that has an accelerometer (which is pretty much every smart device).

This is the plan:

1. Load Human Activity Recognition Data
2. Build LSTM Model for Classification
3. Evaluate the Mode
