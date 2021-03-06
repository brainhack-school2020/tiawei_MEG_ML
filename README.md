# *Machine learning for finger movement source-localized MEG data*

-- author: Tiana Wei

![Machine learning](/NusZ.gif)

## Goals for BHS project
- Familiarize myself with machine learning
- Practice visualization with python

## **Background**
I am currently a PhD1 student in Psychology at University of Toronto. I am supervised by Dr. Jed Meltzer at Rotman Research at Baycrest Hospital. My research interests includes multiple lateralized and contra-lateralized functions, such as language, motor control, and spatial attention, and how the functional networks are altered after unilateral strokes. Especially, my research has been focused on healthy and pathological communications between the two hemispheres. 

In this project, I will use supervised machine learning to train an algorithm that can classify left vs right hand movement based on event-related spectral perturbation (ERSP) signals in the two motor cortices (M1s). This might not be a super exciting research objective but can be a great parctice for me to get started with machine learning :).

## **Project Data**
MEG data were collected from 29 young healthy participants during unilateral finger movements (each particiapnts have two sessions of data: a total of 58 datasets (29/hand); ~115 trials/dataset). 

<a href="url"><img src="https://github.com/brainhack-school2020/tiawei_MEG_ML/blob/master/experiment.png" height="40%" width="40%" ></a>

The MEG data have been time-locked to movement onset recorded through electromyography (EMG), co-registered with participants' structural MRI, and source-localized for ROIs localization. Virtual channels at the source-level were computed for both left and right motor cotices. Time-frequency analysis (ERSP) and connectivity analysis were done in Matlab.

ERSP in M1s:

<a href="url"><img src="https://github.com/brainhack-school2020/tiawei_MEG_ML/blob/master/ERSP.png" height="50%" width="50%" ></a>

*During unilateral hand movement, **contralateral M1 (e.g., Left M1 during right hand movement)** has (1) stronger delta-theta power increase at the movement onset, and (2) stronger beta rebound 500 ms after movement onset compared to ipsilateral M1.* 

## **Objectives**
Based on M1 virtual channel ERSPs during left and right hand finger movement, I would like to train a model to interpret which hand is moving (supervised classification) and practice visualizing results with Python.

## **Deliverables**
- Python scripts for machine learning in Jupyter notebook
- Data visualization in python

## TO-DO LIST
- [ ] load Matlab matrices in python
- [ ] feature selection
- [ ] ML model training/testing
- [ ] results plotting (visualization)
- [ ] update results on github
