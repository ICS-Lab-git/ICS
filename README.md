# ICS Lab
### Information and Cyper Security Laboratory

## Member
### Youngjoo Shin, Taehyun Kim, Taehun Kim, Miok Im, Soojin Kim


## What is ICSL_Detector?
#### Real-time detection on FLUSH+RELOAD attack using Performance Counter Monitor

## Usage
<pre><code>git clone https://github.com/ICS-Lab-git/ICS.git
tar -xvf ICSL_Detector.tar</code></pre>

### How to configure
<pre><code>cd ICSL_Detector
chmod 0755 start.sh
sudo ./start.sh</code></pre>

### How to use
<pre><code>cd CSCA_Detection
sudo ./python3 run.py</code></pre>

### How to training model
<pre><code>./python3 training.py [trainig file path]</code></pre>


## What is Framework?
### Framework on Cache Side-channel Attack Detection Using Real-time Monitoring 

## Usage
<pre><code>git clone https://github.com/ICS-Lab-git/ICS.git
unzip ICSL_Detector2.zip</code></pre>

### How to configure
<pre><code>cd ICSL_Detector
chmod 0755 start.sh
sudo ./start.sh</code></pre>

#### The detection program and telegraf should be run simultaneously.
### How to run the detection program
<pre><code>cd CSCA_Detection
sudo ./python3 run.py</code></pre>

### How to run telegraf
<pre><code>cd telegraf
sudo ./telegraf</code></pre>
