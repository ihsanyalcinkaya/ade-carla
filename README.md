# ade-carla

This is a sample project which contains a base docker file to run [Carla Simulator](https://carla.org/) in [Agile Development Environment(ADE)](https://ade-cli.readthedocs.io/en/latest/index.html).

### Step 1:
Follow the [ADE installation document](https://ade-cli.readthedocs.io/en/latest/install.html).

### Step 2: Clone the project

### Step 3: Build Docker Image
```
docker build -t ade-carla .
```

### Step 4: Start the container as ADE
```
ade start --enter 
```

### Step 5: Run Carla Simulator
```
../carla/CarlaUE4.sh
```

***Note 1***: This sample project is based on [minimal-ade](https://gitlab.com/ApexAI/minimal-ade) project.
***Note 2***: The built image could be pushed and pulled from a remote registry.

