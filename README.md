# Deep Reinforcement Learning for Drug Design with high PCE Values

## REQUIREMENTS
Modern NVIDIA GPU, compute capability 3.5 of newer.
CUDA 9.0.176
Pytorch 1.9.0
Tensorflow 1.8.0 with GPU support
RDKit
Scikit-learn
Numpy
tqdm
Mordred

## PCE
Power Conversion Efficiency (PCE) measures the amount of power output from a device relative to the power input. It's a crucial metric for chemical compounds used in various applications.
What are the effects of PCE value (if its high and if its low): High PCE: Enhanced energy utilization, improved device performance, and lower environmental impact.
Low PCE: Reduced energy conversion efficiency, increased energy wastage, and limited applications.

## METHODOLOGY: 
1) This method uses SMILES to represent the molecules.

2) The combination of deep learning and reinforcement learning is used.

3) Two deep neural networks were trained, one used for generating new molecules and one for predicting the properties of those molecules.

4) In the first phase the generative and predictive models are trained separately.

5) In the second phase, both models are trained jointly with the RL approach to bias the generation of new chemical structures toward those with desired properties.

## PHASE1 TRAINING OF GENERATIVE MODEL:
<img width="485" alt="image" src="https://github.com/Harshinikavuru2608/Deep-reinforcement-learning-for-drug-design-with-High-PCE-Values/assets/125713954/a53473de-c234-4ff4-b200-b094bac40e96">

## TRAINING PROCESS FOR GENERATIVE MODEL:
<img width="566" alt="image" src="https://github.com/Harshinikavuru2608/Deep-reinforcement-learning-for-drug-design-with-High-PCE-Values/assets/125713954/0c2e0369-bc3c-41ee-aa95-d61de3c007dc">

##GENERATOR STEP PHASE1:
<img width="727" alt="image" src="https://github.com/Harshinikavuru2608/Deep-reinforcement-learning-for-drug-design-with-High-PCE-Values/assets/125713954/02cb6457-4d72-49bc-a966-70633db71a15">

##PROPERTY PREDICTION:
<img width="745" alt="image" src="https://github.com/Harshinikavuru2608/Deep-reinforcement-learning-for-drug-design-with-High-PCE-Values/assets/125713954/8887f209-8d0e-402b-b86a-3b4f2332a24e">

##GENERAL PIPELINE OF RL SYSTEM FOR NOVEL COMPOUND GENERATION:
<img width="526" alt="image" src="https://github.com/Harshinikavuru2608/Deep-reinforcement-learning-for-drug-design-with-High-PCE-Values/assets/125713954/77304907-b637-4661-9f11-8fa848c6f9c3">

