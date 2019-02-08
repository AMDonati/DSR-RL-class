# DSR-RL-class-Feb19
Repo for the "Intro to Reinforcement Learning" Class @ DSR

### Set-up of OpenAI gym on the command line

#### Step 1. Install Anaconda
* Windows / Mac: https://www.anaconda.com/distribution/
* Linux - on the terminal: 
* download with wget: `wget http://repo.continuum.io/archive/Anaconda3-4.3.0-Linux-x86_64.sh`
* install with: `bash Anaconda3-4.3.0-Linux-x86_64.sh`


#### Step 2. Create a conda virtual environment and activate it 
* `conda create --name rl-env python=3.6 anaconda`
* `source activate rl-env`

#### Step 3. Install the following dependencies
* `sudo apt-get update`
* `sudo apt-get install golang libcupti-dev libjpeg-turbo8-dev make tmux htop chromium-browser git cmake zlib1g-dev libjpeg-dev xvfb ffmpeg xorg-dev python-opengl libboost-all-dev libsdl2-dev swig`

* `conda install pip six libgcc swig`
* `conda install opencv`

#### step 4. Install gym with pip 
* `pip install gym==0.7.0`
* or you can directly clone the gym repository: 
* `cd
* `git clone https://github.com/openai/gym.git`
* `cd gym`
* `pip install -e '.[all]'

### Additionnal ressources on RL
* https://github.com/AMDonati/RL-ressources-tutos-2018
