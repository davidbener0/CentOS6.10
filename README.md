# CentOS6.10

Este repositorio tem o repositorio vault do centOS 6.10, copie para a pasta /etc/yum.repos.d/ e limpe o cache do yum e atualize.

```bash
yum clean all
yum update
```

também contém o arquivo do grub.conf para inicialização de sua instancia, lembre de ajustar o UUID conforme necessário,  utilize o blkid para pegar o ID atual do seu disco.

