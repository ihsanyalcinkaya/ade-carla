# ade-carla

This is a sample project which contains a base docker file to run [Carla Simulator](https://carla.org/) in [Agile Development Environment(ADE)](https://ade-cli.readthedocs.io/en/latest/index.html).

### Step 0:
Follow the [ADE installation document](https://ade-cli.readthedocs.io/en/latest/install.html).

### Step 1: Build Docker Image
```
docker build -t ade-carla .
```

### Step 2: Start the container as ADE
```
ade start --enter 
```

### Step 3: Run Carla Simulator
```
../carla/CarlaUE4.sh
```


***Note 2***: the built image could be pushed and pulled from a remote registry.

