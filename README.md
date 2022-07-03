# gs-spring-boot (Docker)<br/>

# build<br/>
1- git clone https://github.com/Fares-Saffouri/gs-spring-boot.git<br/>
2- cd gs-spring-boot<br/>
3- docker build -t gs-boot .<br/>

# run
docker run -d -p 8080:8080 gs-boot
# push to docker hub

docker tag gs-boot fares111/gs-boot:1.0.0<br/>
docker push fares111/gs-boot<br/>
![image](https://user-images.githubusercontent.com/70641137/177053248-1dde5023-aba6-4620-8f14-8755b86fc099.png)
