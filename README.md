# Install_firefox_inside_docker_in_RhEL9
step1 : make a docker file

step2 : build the image #docker build -t ayush5858/newos:v1 filename .

step3 : push to docker hub #docker push ayush5858/newos:v1

In local system pull docker image #docker pull ayush5858/newos:v1

in local system rub the command : docker run -it --rm --net=host --env="DISPLAY" --volume="$HOME/.Xauthority:/root/.Xuthority:rw" imagename

step4 : use anywhere to launch the firefox.
