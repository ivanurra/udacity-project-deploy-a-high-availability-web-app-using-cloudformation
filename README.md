## Udacity Cloud DevOps Engineer: High availability web app using CloudFormation
### CD12352 - Infrastructure as Code Project Solution
### Iván Urra

![Architecture](./infrastructure-diagram.jpeg)

## Setup Instructions
### Creating Network Stack
```
cd udacity-project-deploy-a-high-availability-web-app-using-cloudformation
./create.sh udagram-network network.yml network-parameters.json
```

### Updating Network Stack
```
cd udacity-project-deploy-a-high-availability-web-app-using-cloudformation
./update.sh udagram-network network.yml network-parameters.json
```

### Creating Server Stack
```
cd udacity-project-deploy-a-high-availability-web-app-using-cloudformation
./create.sh udagram-servers udagram.yml udagram-parameters.json
```

### Updating Server Stack
```
cd udacity-project-deploy-a-high-availability-web-app-using-cloudformation
./update.sh udagram-servers udagram.yml udagram-parameters.json
```