# electronjs
desktop application

Installation:
1. npm init -y
2. npm install --save-dev electron

To run you app in developer mode:
3. npm start




Building your application:
1. sudo npm install -g electron-builder
2. electron-builder --version

You use the flags -mwl to build applications for macOS, Windows, and Linux respectively.
3. electron-builder -mwl

Build applications for macOS:
3.1. electron-builder --mac

Build applications for Windows:
3.2. electron-builder --win

Build applications for Linux:
3.3. electron-builder --linux