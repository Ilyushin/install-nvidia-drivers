# Install NVIDIA drivers
There are some script, which help you to install Docker and NVIDIA drivers on Ubuntu Server 18.04.4 LTS. 

## Scripts:
1. Install a last version of the drivers
```shell script
chmod +x ./scripts/install_nvidia_drivers_last_version.sh
./scripts/install_nvidia_drivers_last_version.sh
```

2. Install a specific version of the drivers. In the current version, the script will install 440.33.01 
```shell script
chmod +x ./scripts/install_nvidia_drivers_last_version.sh
./scripts/install_nvidia_drivers_specific_version.sh
```

3. Install Docker 
```shell script
chmod +x ./scripts/install_docker_with_gpu.sh
./scripts/install_docker_with_gpu.sh
```

