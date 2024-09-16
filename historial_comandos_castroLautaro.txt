ssh-keygen -t ed25561
ssh-keygen -t ed25519
cat /home/vagrant/.ssh/id_ed25519.pub
pwd
mkdir repoguittp
ls -l
cd repoguittp
ls -l
git clone  https://github.com/Lautaro-Castro/TP_AySO.git
ls -l
cd TP_AySO/
man grep 
grep -i Home_url /etc/os-realease
grep -i Home_url /etc/os-release
whoami
echo “Usuario=$(whoami)” > datos_usuario.txt
git config --global user.email lautarocastro1998@gmail.com
git config --global user.name Lautaro-Castro
git add .
git commit -m "ADD: agregado 1er ejercicio
sobre datos_usuarios.txt"
man grep 
grep "model name" /proc/cpuinfo | head -n 1 >> historial_comando_LautaroCastro.txt
git add .
git commit -m "feat: Añadiendo informacion de CPU"
grep -v "nologin" /etc/passwd | head -n 10 | sort -t: -k7>lista_ordenada
git add .
git commit -m “ADD: Listado de usuarios ordenada”
git add .
git commit -m "ADD: agregado 1er ejercicio"
ls -l
man grep
man -k dump | grep traffic
echo -e "uso el comando man -k dump | grep traffic para obtener el tcpdump el cual sirve para limpiar los archivos y este comando me devolvio: tcpdump (8)          - dump traffic on a network"   
echo -e "uso el comando man -k dump | grep traffic para obtener el tcpdump el cual sirve para limpiar los archivos y este comando me devolvio: tcpdump (8)          - dump traffic on a network" > comandodump   
mv comandodump comando_dump_net
ls -l
git add .
git commit -m "ADD: Comando para Capturar y analizar el tráfico de red"
cat <<EOF >> README.md
Alumno: Lautaro
División: 313
Turno: Noche
EOF

git add .
git commit -m "FIX: Edicion del README"
pwd
history
history -a
