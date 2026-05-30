# 🚀 Easy WordPress Docker Setup

This repository contains the declarative blueprint to automatically set up a WordPress site and a MySQL database using Docker Compose. 

## Prerequisites
Before you begin, make sure you have Docker and Docker Compose installed on your system (whether that is a local machine, a Kali VM, or a cloud server).

## How to Use This Blueprint

1. Clone this repository or download the docker-compose.yml file to your machine.
2. Open your terminal and navigate to the folder where you saved the file.
3. Run the following command to download the images and spin up the containers:
   ```bash
   docker-compose up
4. Open your web browser and go to http://localhost (or the IP address of your VM/server).
​5. Complete the famous 5-minute WordPress installation wizard!
​How to Tear it Down
​If you want to delete the environment and wipe the data clean, run:
   ```bash
   docker-compose down -v
