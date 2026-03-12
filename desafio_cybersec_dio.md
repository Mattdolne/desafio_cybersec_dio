+================================
DESAFIO CYBERSEC - DIO
+================================

Para este desafio, originalmente, rodávamos os seguintes códigos em
uma distro Kali:

Acesso root: sudo su
Iniciando o setoolkit: setoolkit
Tipo de ataque: Social-Engineering Attacks
Vetor de ataque: Web Site Attack Vectors
Método de ataque: Credential Harvester Attack Method 
Método de ataque: Site Cloner
Obtendo o endereço da máquina: ifconfig
URL para clone: http://www.facebook.com

Não usei Kali Linux e sim Pop_OS. Portanto, antes de prosseguir 
com o setoolkit, precisei seguir a configuração presente no
repositório original:
https://github.com/trustedsec/social-engineer-toolkit

instalação do python (caso não tenha):
python3 setup.py 

Instalação do setoolkit:
git clone https://github.com/trustedsec/social-engineer-toolkit/ setoolkit/
cd setoolkit