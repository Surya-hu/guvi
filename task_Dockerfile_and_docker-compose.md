Create a docker file, docker-compose file which when executed must display your basic details in the website

Cloned the repository using “git clone https://github.com/Surya-hu/my-nodejs-app.git”

And created Dockerfile “ vi Dockerfile”

![](Aspose.Words.de604882-e775-41b0-8d89-3edde9f2b326.001.png)

![](Aspose.Words.de604882-e775-41b0-8d89-3edde9f2b326.002.png)

Created docker image using: “docker build -t my-node-img .”

And listed the images available using “docker images”

To create the container and run: “docker run -itd -p 8000:8000 --name my-node-app my-node-img” as shown below

![](Aspose.Words.de604882-e775-41b0-8d89-3edde9f2b326.003.png)
