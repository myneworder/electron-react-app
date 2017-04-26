# Goal
Electron with React JS starter Application.

# Access Electron from React App
```
const electron = window.require('electron');

const fs = electron.remote.require('fs');
const ipcRenderer  = electron.ipcRenderer;
```
