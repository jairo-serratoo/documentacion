# Instalacion de minikube en una maquina virtual Ubuntu Focal 20.04 en virtualbox.

- Instalamos docker siguiendo las instrucciones de la pagina: https://docs.docker.com/engine/install/ubuntu/
   - La forma de instalacion es: Install using the apt repository
- Instalamos kubectl siguiendo las instrucciones de la siguiente pagina: https://kubernetes.io/es/docs/tasks/tools/install-kubectl-linux/
- Instalamos minikube con las instrucciones de la sigueinte pagina: https://minikube.sigs.k8s.io/docs/start/?arch=%2Flinux%2Fx86-64%2Fstable%2Fbinary+download
   - Al haber ejecutado con sudo la instlacion de docker, manda el error de que no se puede conectar al daemon, para resolverlo hay que agregar el usuario actual al grupo de usuarios de docker: 'sudo usermod -aG docker $USER && newgrp docker'
