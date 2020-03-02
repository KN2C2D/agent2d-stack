![2D Soccer Simulation Screenshot](https://rcss.ir/docs/2D/FA/img/doc/intro/2d-overview-field.jpg)

# **Agent2DStack**   

![Agent2D Buid + Binary](https://github.com/KN2C2D/agent2d-stack/workflows/Agent2D%20Buid%20+%20Binary/badge.svg?event=push)

This project is based on **[HELIOS Base](https://osdn.net/projects/rctools/releases/)** (Agent2D 3.1.1 & Librcsc 4.1.0) & Licensed under _GNU GPL 3_. 

## First time build

1. Install dependencies.

   ```bash
   sudo apt-get update && sudo apt-get install -y g++ build-essential libboost-all-dev qt4-dev-tools libaudio-dev libgtk-3-dev libxt-dev bison flex
   ```

2. Clone this repository.

   ```bash
    git clone git@github.com:KN2C2D/agent2d-stack.git && cd agent2d-stack
   ```

3. Then build agent & lib with included script:

   ```bash
   ./makeFirstTime.sh
   ```

   Done ! 🙂

## Build after changes

After changing any part of the code you can easily build it with `makeAll.sh` & `makeAgent.sh`

## Run A Game

After building the project, you can run the team with these instructions:

1. Open a terminal and run [rcssserver](https://github.com/rcsoccersim/rcssserver)  

   ```bash
   rcssserver
   ```

2. Open new terminal and got to project folder then run your team

   ```bash
   cd agent2d-stack/Agent/src
   ./start.sh -t YOUR_TEAM_NAME
   ```

3. Now open a monitor like [rcssmonitor](https://github.com/rcsoccersim/rcssmonitor) and watch the game 

   ```bash
   rcssmonitor
   ```

> For further instructions you can use [this link](https://github.com/ibots/tutorial) (English) or [مستندات شبیه‌ساز دوبعدی فوتبال](https://rcss.ir/2D/FA)(Farsi).
