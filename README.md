# MJU (M-Unity's Jellyfin Uploader)
A simple, easy-to-use and self-hosted jellyfin media uploader straight to your jellyfin volume folders.
Upload media from anywhere on your device or from other devices on your network or you can expose it and upload media from anywhere in the world (Not recommended, unless you know what you're doing).

## ⭐ Features

- Upload videos straight to jellyfin volume
- Selecting which folder inside the jellyfin volume do you want to save (movies, series, courses, etc)
- Uploading progress bar

## 🔧 How to Install

Requirements:
- [Docker](https://docs.docker.com/engine/install/) 
- [Docker Compose](https://docs.docker.com/compose/install/)

### Basic
- To run the MJU on top of docker just clone the repo and deploy it with docker-compose as follows:
    ```bash
        git clone https://github.com/M-UnityDev/MJU.git
        cd MJU
        docker-compose up -d --build
    ```
- To run the MJU without docker, using your host python to run it do the following steps:
    ```bash
        git clone https://github.com/M-UnityDev/MJU.git
        cd MJU
        RUN pip3 install --no-cache-dir -r requirements.txt
        flask run # Or python3 app.py 
    ```
MJU is now running on http://localhost:5005