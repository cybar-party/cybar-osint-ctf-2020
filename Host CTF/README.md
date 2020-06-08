# Local CTF Instance
If you get stuck along the way, feel free to reach out for us on [Discord](https://discord.gg/KsSh24V) for a hand!

## Install Docker
* [Install Docker for your appropriate Operating System](https://docs.docker.com/get-docker/)

## Start CTFd Container
* Test that Docker is installed and correctly running
![screen_1.PNG](Files/screen_1.png)

* Start a fresh CTFd container:
```
docker run -d -p 8000:8000 ctfd/ctfd:mark-2.3.3
```

* Browse to `http://localhost:8000` 

## Setup and Import
* Fill in the CTFd setup details with random information (It'll all get overwritten once you import the backup)

* Once you've passed the basic setup screen, click the `Admin Panel` buttom.
![screen_2.PNG](Files/screen_2.png)

* Click `Config > Backup > Import > Choose File`
![screen_3.PNG](Files/screen_1.png)

* Download the [CYBAR OSINT CTF EXPORT](https://github.com/cybar-party/cybar-osint-ctf-2020/raw/master/Host%20CTF/CYBAR%20OSINT%20CTF%20EXPORT.zip)

* Upload the Export zip file and hit `Import`

* If it successfully imports you should land back on the CTFd Login page

* Login with `admin` as Username and Password