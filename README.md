# TPM-Notificador #

Script que reporta al usuario mediante notificación de escritorio que el dipositivo se encuentra en riesgo de bloqueo.


### Cómo: ###
* Se extraen los datos mediante tpmdoctor
* Se comprueba que la cantidad de ciclos / fecha de expiración estén por fuera del rango de riesgo
* Si el dispositivo está en riesgo, notifica al usuario

### Requerimientos ###
* Python <= 2.7
* gi (Gtk 3+)
* tpmdoctor64 (paquete tpmdoctor en el repo de huayra)

### dev-tools (?) ###
htpmnoti [-h] [-t] [-d]
* -h          Muestra este mensaje
* -t  --test  Simula dispositivo en riesgo para mostrar notificador
* -d  --data  Muestra datos extraidos con el tpmdoctor64 en notificador

### Proyecto original ###
Este paquete es representativo del [proyecto original](https://bitbucket.org/lahire/huayra-tpmnotificador) de Nicolás Girogetti
