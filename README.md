# *Machine learning for personalized post-stroke neuromodulation (or ML for finger movement source-localized MEG data)*

![Machine learning](/NusZ.gif)

## **Background**
Hi! My name is Tiana Wei. I am a PhD1 student in Psychology at University of Toronto. My research interests includes multiple lateralized and contra-lateralized functions, such as language, motor control, and spatial attention, and how the functional networks are altered after unilateral strokes. Especially, my research has been focused on healthy and pathological communications between the two hemispheres. 
Healthy excitatory and inhibitory interhemsispheric interactions are disrupted after stroke. As promising rehabilitation tools, non-invasive brin stimulation (NIBS) techniques have been used to modulate the damaged networks to improve functional recovery. However, different stroke patients may require different directions of neuromodulation (e.g., whether we should excite the perilesional areas or the contralesional areas) based on a number of individual factors (e.g., gender, age, stroke duration, storke size/site, etc...). I reason that this is where machine learning can step in to help develop more personalized NIBS intervention by assessing patients' individual factors and directing them to the optimal NIBS direction. 

## **Still working on accessing open data. Therefore, a backup project :).**
Since I am not too confident about how to get enough data to train the prediction for optimal NIBS yet (I am exploring possible open data or I might need to do a meta-analysis on existing literature). A potential back-up project would be to do ML on the existing finger movement MEG data from my Master's thesis. For the purpose of practicing ML on MEG data, I can train an algorithm to classify left and right hand movement's corresponding interhemispheric connectivity signal.

## **Project Data**
Option 1: Access open data from NIBS post-stroke patient studies.
Option 2: Use my exisitng MEG data from 29 young healthy participants during unilateral finger movements (each particiapnts have two sessions of data: a total of 58 datasets for each hand movement senario). The MEG data have been co-registered with participants' structural MRI and source-localized for ROIs localization. Virtual channels at the source-level were computed for both left and right motor cotices. Phase-based and amplitude-based connectivity measures where derived between motor corticies separated by the moving hand (left hand moving vs right hand moving).

## **Objectives**
Option 1: Train an algorithm based on stroke-patients' background features (e.g., gender, age, stroke duration, storke size/site, etc...) and their NIBS intervention results. Then, use the algorithm to predict the optimal NIBS parameters for specific patients.
Option 2: Train an algorithm based on motor cortices' virtual channel data during left and right hand finger movement. The goal is to train the machine to interpret which hand is moving based one the MEG data (event-related spectral pertrbation or connectivity signals).

## **Deliverables**
- Python scripts for machine learning in Jupyter notebook
- Results visualization in python
