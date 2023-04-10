FROM archlinux:latest  
ENTRYPOINT ["echo", "Hello"]  
CMD ["World"]  

This Dockerfile specifies that the base image should be Arch Linux with the latest version. It sets the default command to echo Hello as the entry point for the container, with World as the default argument. This means that when you run a container from this image, it will print Hello World by default, but you can provide a different argument if you want
