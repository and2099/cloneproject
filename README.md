# cloneproject
Debian-lxde-core tar.gz distro minimalista.
 
chroot install debian linux

1- descompacte o arquivo em uma partição, pendrive, hd , etc... 

2- entre no sistema descompactado via "chroot"

3- mount -t none proc

4- mount --rbind /sys sys

5- mount --rbind /dev dev

6- chroot /mnt/local /bin/bash

7- e instale (pelo Apt ou compilado) um KERNEL x86 de sua preferencia e o GRUB caso queira tornar o sistema inicializavel

8- senha do root, caso não mude antes de instalar (passwd root) ~> "rootroot"

9- não esta bem explicado, mas pra bom entendedor meia palavra basta.
- 
10- Faça um bom proveito, por que eu fiz ;) 

11- Sugestões criticas e colaborações são sempre bem vindas...


