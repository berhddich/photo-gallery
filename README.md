# Photo Gallery App


## Overview

This is a simple photo gallery app built with Ionic Angular, utilizing Capacitor for native functionality and the Camera plugin for capturing photos.

## Features

- **Take Photos:** Capture and save photos using the device's camera.
- **Gallery:** View a gallery of captured photos.
- **Delete Photos:** Remove unwanted photos from the gallery.

## Installation

Before running the app, make sure you have Node.js and npm installed on your machine. Then, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/berhddich/photo-gallery.git
    cd photo-gallery
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Add the platform you want to run the app on (iOS/Android):

    ```bash
    npx cap add ios
    npx cap add android
    ```

4. Copy the web assets to the native projects:

    ```bash
    npx cap copy
    ```

## Usage

### Web

To run the app in a web browser:

```bash
ionic serve
