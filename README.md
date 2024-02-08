# Gallica BNF app by EPITA 
### Authors : 
Vincent THONG, Zoe Sellos, Yanis Farhat, Benjamin Clene, Maxime Boy-Arnould
### Supervised by: 
Jean-Philippe Moreux (BNF)
Joseph Chazalon (EPITA)
### Requirements to run the environment 
- Nvidia GPU
  Nvidia Container Toolkit : https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html

### Docker Tutorial 
- https://docs.docker.com/get-started/
- Docker: https://docs.docker.com/get-docker
  Docker supported GPU : https://docs.docker.com/config/containers/resource_constraints/#gpu

### Command to run:
Building image : docker compose build
Start container :  docker compose up

After this commands you can get a link with a tocken, it is necessary to go to this link. 
The port is localhost:8888.
You can also access to the environment in VScode by attaching to it with Docker Extension.

### Running the app 
cd app; python3 app.py

The port to access is http://localhost:7860/   (a link will appear with 0000:7860 this one doesn't work)

### The app : 
Only "Evaluate an image" tab work
#TODO : 
- debug gallery
- add metrics cocopanoptic
- add more visualisation