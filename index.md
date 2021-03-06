# eReKon

Yet another web recon tool But beautiful (not the code). 

## sneak peek

#### Landing page
![landing](https://raw.githubusercontent.com/rubenkharel/eReKon/main/repoAssets/landing.png)
#### Login/Register
![login](https://raw.githubusercontent.com/rubenkharel/eReKon/main/repoAssets/login.png)
#### Scanned data sample
![Sample](https://raw.githubusercontent.com/rubenkharel/eReKon/main/repoAssets/scanner.png)
#### Dashboard
![Dash](https://raw.githubusercontent.com/rubenkharel/eReKon/main/repoAssets/dash.png)

## Features
- Dark Mode and only that.
- Easy to find information like CVE, Port informations, Status infos, IP info.
- Login/Register
- Saves all the scans on database for later use
- Smooth UX/UI
#### Fast Scan
- Subdomain Scanning (findomain)
- PortScanning (evilscan)
- Version Scanner (Wappalizer)
- Screenshots (Puppeter iguess)

#### Effective Scan (UNDERDEVELOPMENT)
- All of the above from Fast scan
- Subdomain Bruteforce (ffuf) 
- Directory scanning (??idk??) 
#### Tech Used
- React.js + Bootstrap (Frontend)
- Node.js (Backend) REST API
- MongoDB (Database)
- Express (Server)

## Install

### Manual
#### FrontEnd 

> $git clone https://github.com/rubenkharel/erekon

> $cd erekon/frontend

> $npm install

> $npm start

#### Backend

> $cd erekon/backend

> $npm install

> $npm start

#### Database

Makesure you have mongod working properly on your system

> $mongod --noauth --port 4000 --dbpath ~/where/to/create/your/database

or you can just get a free mongodb cluster(ig) and modify MONGO_CONNECT's value on `.env` file.


### Docker???
I still dont know the D of docker. You can send PR if you are willing to create a dockerfile

## Warning and Some infos about repo.

Vulnerable af, host it only in private environment.

Since, this was the first ever (maybe second, idk) project I built after learning Node.js, I believe its very messy with bad practices... so, it might make you go bang your head on wall if you start doing code review.

But I assure you this repo is very beginner friendly to get you started on opensource contribution.

Create issue if you have any feature request, which I never may build unless I get some free time and get high and think that actually is a great feature to implement.

PR are more then welcome, Any kind of PR... Readme update, READ_BEFORE_CONTRIBUTE.md? kinda thing, or bug fixes? dockerimage? code refactor? anything.. just send PR. I dont have to get high to consider approving PRs btw. 

