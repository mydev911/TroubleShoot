## Jenkins access deney to docker

####### https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Fix-Jenkins-Docker-Permission-denied-daemon-error#:~:text=To%20fix%20the%20Jenkins%20Docker,in%20the%20terminal%20and%20reboot.&text=Many%20organizations%20struggle%20to%20manage,The%20service%20automates%20...

On jenkin server on root user....

```
sudo usermod -a -G docker jenkins
```
