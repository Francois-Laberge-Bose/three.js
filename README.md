Gooey Three
========
Gooey experiements forked off of the three.js repo. Mostly it's slight modifications to their example code.


### Access demos via public link

 1. Go to the Oculus browser in your headset
 1. Type in: https://francois-laberge-bose.github.io/three.js/
 1. Altneratively, use this: https://bit.ly/3tUuKWq

### Running Demos Locally

```
git clone git@github.com:Francois-Laberge-Bose/three.js.git
cd three.js
# In one tab
npm run server
# In anoother tab
npm run proxy
# Find your computers IP, then go the browser on your headset and type
https://<your IP>:3000
# You'll be blocked by a security warning, accept the risks
# You'll land on a webpage with the list of demos
# Try each demo

### Development

**Debug Quest 2 Web Pages**
Read this basically: https://developer.oculus.com/documentation/oculus-browser/browser-remote-debugging/

 1. Install Android Platform Tools so you can debug the Oculus Browser from your development machine
 ```brew install android-platform-tools```
 1. Open: chrome://inspect/#devices

**High Fidelity**

 - Developer panel: https://account.highfidelity.com/dev/account
 - https://docs.highfidelity.com/latest/index.html