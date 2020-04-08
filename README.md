# ICS Lab
#### Information and Cyper Security Laboratory

## Member
#### Youngjoo Shin Taehyun Kim Taehun Kim Miok Im Soojin Kim

## What is ICSL_Detector?
#### Real-time detection on FLUSH+RELOAD attack using Performance Counter Monitor

## Usage
### Clone the repo:
  git clone
  
  tar -xvf ICSL_Detector.tar
  
  cd ICSL_Detector
  
  chmod 0755 start.sh
  
  sudo ./start.sh
  
  cd CSCA_Detection
  
### How to use:
  sudo ./python3 run.py

### How to training model:
  ./python3 training.py [trainig file path]
  
#### To training this machine learning model, using Intel PCM as CSV mode. (./pcm-icsl -e icsl -csv=[path]). And then, add to data to training_file.csv. Order of csv data like this.

#### IPC,L1MISS,L2MISS,L3MISS,Branch,Result
  Result - 0 : Normal state
  1 : FLUSH+RELOAD attack
  2 : FLUSH+FLUSH  attack
  3 : PRIME+PROBE  attack


## What is Framework?
### Framework on Cache Side-channel Attack Detection Using Real-time Monitoring 
