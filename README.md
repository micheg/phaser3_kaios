# Intro
This is a Phaser JS III template for Kaios.

This use the simple parcel bundler.

# How
Once the repository has been cloned, initialize with:

    npm install

# after installation
The following commands will then be available:
* npm run dev (development mode)
* npm run build (deploy mode)
* npm run make_app (prepare the zip for the Kaios store, it works only on Unix Like)

# recommended
* adb
* platform sdk
* gdeploy

# test

## on browser

    npm run dev

## on device

    npm run build
    gdeploy ./dist
