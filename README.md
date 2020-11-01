# Chidur.io Private Server Template

## Quick Start Guide

1. Click the top left where it says **arras-template**
2. Remix the project
3. Give your new project a name
4. Your private server name will be at <http://arras.io/#private=arras-template.glitch.me> (replace `arras-template` with it's new name)

## More Information

1. Open the file at the left named `🔑 .env`
2. Fill it in with
```
SECRET=aSecretPasswordHere
```
3. Open the private server with <http://arras.io/#private=arras-template.glitch.me;aSecretPasswordHere> (replace `aSecretPasswordHere` with the password)
4. The map/config data are in the `config.js` file
5. The tank data are in the `lib/definitions.js` file
6. Other stuff (score curve, stat amount) are in the `server.js` file

## Breaking Changes

Breaking changes are important updates to the template that you should do on your server, as otherwise it may stop functioning. The last breaking change is on April 10th, 2019. If you've made a private server before that day, it may no longer work without this update. See `CHANGELOG.md` for details.

## Change Glitch -> OpenShift

Glitch only allows for a very limited amount of CPU, RAM, and disk space. If your server have gotten lots of traffic, it may be worth it to switch to OpenShift. Although the process is free, it's quite complicated and will take a bit of time. See `OPENSHIFT.md` for details. (NOTICE: the tutorial is not yet complete)