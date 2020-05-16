# Processo de CI/CD com Laravel no Google Cloud Platform

* O intuito deste projeto é realizar os processos de CI e CD no Google Cloud Platform a cada Pull Request que é feita na branch master

* Projeto estruturado da seguinte forma:
    * Container app => Aplicação utilizando Laravel
    * Container nginx => Servidor Web Nginx
    * Container redis => Servidor Redis
    * Container db => Banco de Dados MySQL
    
* Na pasta k8s, estão todos os arquivos para serem utilizados no Kubernetes 

* Comando para criar a senha secreta no GCP `kubectl create secret generic mysql-pass --from-literal=password='senha_bd'`
