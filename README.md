![2D Soccer Simulation Screenshot](https://rcss.ir/docs/2D/FA/img/doc/intro/2d-overview-field.jpg)

# **Agent2DStack**   

This project is based on **[HELIOS Base](https://osdn.net/projects/rctools/releases/)** (Agent2D 3.1.1 & Librcsc 4.1.0) & Licensed under _GNU GPL 3_. 

## Build for first time

1. Install dependencies.

   ```bash
   sudo apt-get update && sudo apt-get install -y g++ build-essential libboost-all-dev qt4-dev-tools libaudio-dev libgtk-3-dev libxt-dev bison flex
   ```

2. Clone this repository into your machine.

   ```bash
    git clone git@github.com:KN2C2D/agent2d-stack.git && cd agent2d-stack
   ```

3. Then build agent & lib with included script:

   ```bash
   ./makeFirstTime.sh
   ```

   Done ! 🙂

## Build after changes

After changing any parts of code you can easily build your code with `makeAll.sh` & `makeAgent.sh`

## Run A Game

After build the project, you can run this team with these instructions:

1. Open a terminal and run [rcssserver](https://github.com/rcsoccersim/rcssserver)  

   ```bash
   rcssserver
   ```

   

2. Open new terminal and got to project folder then run your team

   ```bash
   cd Agent2DStack/Agent/src
   ./start.sh -t YOUR_TEAM_NAME
   ```

3. Now open a monitor like [rcssmonitor](https://github.com/rcsoccersim/rcssmonitor) and watch the game 

   ```bash
   rcssmonitor
   ```

> For further instructions in English you can use [this link](https://github.com/ibots/tutorial) or [مستندات شبیه‌ساز دوبعدی فوتبال](https://rcss.ir/2D/FA).
