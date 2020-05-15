# bodysoft-proxy

## Para funcionamiento en Windows
En el archivo app.cofig 

upstream api_gateway_node {
     
     server host.docker.internal:3800;
  }
  
No hacer commit con esta dirección, para mantener el funcionamiento en AWS
## Para funcionamiento en Linux
Dejar como esta 

upstream api_gateway_node {
      
      server 172.17.0.1:3800;
  }

