#  Simple Docker Container for Echo Server

# Description

# installing
open your terminal windows, enter the following commands
```
git clone https://github.com/lbaitemple/lbaiDocker
```

yOu may have to install docker-compose
```
sudo apt  install docker-compose -y
```

If verything is successful, you can run
```
docker-compose build
```

# Execute Code, open terminal 1
```
docker run -it bionic-bai:latest
```
# Open terminal 2

```
docker-compose --profile echoserver up
```
