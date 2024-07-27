# Customize Container for ubuntu Kasm



## build image 

```
docker build -t username/kasmweb:tag .
```



## run image locally 

```
docker run --rm -it --shm-size=512m -p 6901:6901 -e VNC_PW=password xcad2k/hackbox
```

![Screenshot 2024-07-27 031356](https://github.com/user-attachments/assets/2331919c-c4c7-4745-8b55-10305410104e)


## More info

### christianlempa-hackbox

https://github.com/christianlempa/hackbox
