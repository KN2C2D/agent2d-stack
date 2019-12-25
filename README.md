# **Agent2DStack**   

This project is based on **[HELIOSbase](https://osdn.net/projects/rctools/releases/)** (Agent2D 3.1.1 & Librcsc 4.1.0) & Licensed under _GNU GPL 3_. 

## Build for first time
1. Install dependencies.

   ```bash
   sudo apt-get update && sudo apt-get -y install g++ build-essential libboost-all-dev qt4-dev-tools libaudio-dev libgtk-3-dev libxt-dev bison flex
   ```

2. Clone this repository into your machine.

   ```bash
    git clone https://github.com/KN2C2D/Agent2DStack.git && cd Agent2DStack
   ```

3. Then build agent & lib with included script:

   ```bash
   ./makeFirstTime.sh
   ```

   Done !

Now you can run this project but first run rcssserver then change directory to Agent/src and run start.sh:

> ./start.sh

For further instructions refer to INSTALL file provided or to this [link](https://github.com/ibots/tutorial)
