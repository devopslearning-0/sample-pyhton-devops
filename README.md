# sample-pyhton-devops
Sample python file for DevOps test

Pre-rquisites - Docker installation
Check system - 
- ```sudo docker version```
- ```sudo docker pull hello-world```
- ```sudo docker run hello-world```
- If it shows "Hello from Docker!". Make sure docker is working fine.

----------------------------Run this python files in docker------------------------------

| Instructions | Commands |
| First clone this file to your local machine | ```git clone https://github.com/devopslearning-0/sample-pyhton-devops.git``` |

| Enter into the file |  ```cd sample-pyhton-devops``` | 

| Build docker image|  ```sudo docker build -t <dockerhub-username>/<image-name>:<version> .``` |

| example |  ```sudo docker build -t sbssunu/demopyapp:v1.0.0 .``` |

| Check if docker image created | ```sudo docker images``` |

| Run docker image permanently(in the background) | ```sudo docker run -d -p 5000:5000 --name server1 sbssunu/demopyapp:v1.0.0``` |

| Run docker image instantly(closes if you close terminal) | ```sudo docker run -it -p 5000:5000 --name server1 sbssunu/demopyapp:v1.0.0``` |

| Access your python app | http://<public/vm-ip-address>:5000``` |


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |
