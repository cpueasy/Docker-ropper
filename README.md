# Docker-ropper
A Docker Container designed for crackme's and binary explotation CTF Challenges, Inspired from LiveOverflow and fixed

### Linux Docker Setup
```bash
sudo apt install docker.io -y
````

#### Building Process
```bash
git clone https://github.com/cpueasy/Docker-ropper.git && Docker-ropper && docker build -t ctf:ubuntu19.10
```

#### Running The Container
```
docker exec -it ctf /bin/bash
```
