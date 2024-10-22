# TP3-TS

## Instalação e inicialização:

+ Dentro da pasta **scripts** executar os comandos de instalação e inicialização respetivamente 
  + sudo bash install.sh
  + sudo bash start.sh

## Para apagar todos os ficheiros 
  + sudo bash uninstall.sh
## Aceder aos logs

+ cat /etc/rsyslog.d/monitord-logs.conf
+ cat /var/log/monitord-logs.log

## Utilização do serviço

+ Definir um ficheiro para ser vigiado
  + Criar um ficheiro qualquer ou utilizar um já existente
    + Na pasta, para adicionar o ficheiro àqueles que serão vigiados, executar:
      + /etc/mon -a <path do ficheiro>
        + Para verificar se ocorreram alterações nos ficheiros vigiados basta aos logs com o comando mencionado anteriormente para visualizar qual o ficheiro que foi alterado, assim como a data da alteração
    
+ Verificar registos:
  + cat /etc/monitord-registry.txt

+ Definir um ficheiro para deixar de ser vigiado
  + /etc/mon -d <path do ficheiro>

## Finalização: Terminar o serviço

+ Dentro da pasta **scripts** executar o comando:
  + sudo bash stop.sh
  
  
  
# Contributors:

[Rui Carvalho](https://github.com/RuiC10)
[Ana Luísa](https://github.com/Analucar)

