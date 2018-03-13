# OpenEBS-Assessment--1
[0] Create a GitHub repo which should have the source files for showing "Hi, <username>" in a browser.
Try to pass the <username> from the container, during it's runtime. Don't hardcode the username anywhere.
  
[1] Now since we all love to containerize things, write a Dockerfile for the same. (pip is required to run this file, if there is no pip in your system then you can install it by using command: sudo apt-get install -pip)

[2] Write a Kubernetes YAML spec for running it in a pod.

[3] To keep the pod running write a deployment and a service YAML.

[Sanitychecks]
- Your GitHub repository should have
  - source code
  - Dockerfile
  - Yaml file for pod, deployment and a service

[Bonus points] 
[0] Show the hostname of the container in the browser.

Hints:
[0] https://help.github.com/articles/create-a-repo/

[1] See the official docs of Docker at docs.docker.com

[2] & [3] Try `kubectl explain -h` or read some 

If the official docs make you feel dizzy try http://kubernetesbyexample.com/
