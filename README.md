# ACiD
Automatic Continuous Integration and Delivery Suite

![](/images/underCon.jpg)


# 1. Set Up ACiD Suite 

* Instala y configura todas las herramientas para la suite con base en los parametros de entrada
* Los parametros son tomados del pipeline o directamente como extra vars si se usa el playbook desde una CLI
* Instala Jenkins, Maven, NPM, SonarQube, Nexus / Artifactory, Docker / Buildah, Kubernettes, Terraform, Ansible
* El *provider* o red destino para aplicar la infraestructura tambien debe ser pasado como parametro
* Azure / AWS / GCP / On-Prem

# 2. Use ACiD Pipeline 

* Descarga el codigo y complia la aplicacion con base en los parametros de entrada
* Los parametros son tomados del pipeline o directamente como extra vars si se usa el playbook desde una CLI
* Un pipeline de CI/CD con Jenkins, utilizando Groovy
* GitHub como sistema de control de versiones (SCM)
* Maven / NPM para construir una aplicación Java / Node.js
* Docker / Buildah, Kubernetes
* Terraform para la Infraestructura como Código (IaC),
* Ansible para la configuración del sistema y el despliegue en Azure Cloud


## Sample Video Demonstrations

Sample video output can be found out for visual experience [here](https://youtu.be/EE1Z_9F98vU) :

<a href="http://www.youtube.com/watch?feature=player_embedded&v=EE1Z_9F98vU" target="_blank"><img src="http://img.youtube.com/vi/EE1Z_9F98vU/0.jpg" alt="IMAGE ALT TEXT HERE" width="530" height="360" /></a>

