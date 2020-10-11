# POC Using Ory hydra and oathkeeper integrated with istio for auth



## Prerequirements

- Kubernetes 1.17.11
- Istio 1.7.1
- Helm 3
- Node.js 12.19. LTS 
- Tilt Latest

## Tasks

- [ ] **Install development tools**
  - [ ] Install Kind
  - [ ] Install Helm
  - [ ] Install istioclt
  - [ ] Install Tilt 

- [ ] **Define a initial project structure**

- [ ] **Kubernetes configuration**
  - [ ] Create a local registry
  - [ ] Create a local cluster 
  - [ ] Create a Helm Chart to deploy:
    - [ ] Ingress controller with Nginx
    - [ ] Network Load Balancer with MetalLB
    - [ ] Istio
      - [ ] Configure istio gateway service
  - [ ] Automate helm deploy with Tilt

- [ ] **Update helm chart with Ory Hydra basic configuration**
- [ ] **Update helm chart with Ory Oathkeeper basic configuration**
 
 - [ ] **Demo app: Identity Provider**
    - [ ] Create a node.js project structure/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an authetication endpoint based on user and password
    - [ ] Integrate with Ory Hydra in order to generate access and refresh tokens
  
 - [ ] **Demo app: Login Backend For Frontend**
    - [ ] Create a node.js project structure/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an authetication endpoint based on user and password
    - [ ] Integrate with Ory Hydra in order to generate access and refresh tokens
  
 - [ ] **Demo app: Login Frontend**
    - [ ] Create a ReactJS project/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an authentication page integrated with Identity Provider

- [ ] **Demo app: Business Metrics Microservice**
    - [ ] Create a node.js project structure/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an endpoint to retrieve some metrics to display in dashboard

- [ ] **Demo app: User Microservice**
    - [ ] Create a node.js project structure/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an endpoint to retrieve current user personal data

- [ ] **Demo app: Dasboard Backend For Frontend**
    - [ ] Create a node.js project structure/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an endpoint that gets current user data
    - [ ] Create an endpoint to retrieve some metrics data
    - [ ] Integrate with Ory Hydra in order to generate access and refresh tokens
  
 - [ ] **Demo app: Dasboard Frontend**
    - [ ] Create a ReactJS project/ foundation
    - [ ] Create Dockerfile
    - [ ] Create helm chart to setup the project
    - [ ] Automate helm deploy with tilt
    - [ ] Create an dasbhoad page with metrics and user data
  
 - [ ] **Explore configurations on ory hydra and oathkeeper**
  
