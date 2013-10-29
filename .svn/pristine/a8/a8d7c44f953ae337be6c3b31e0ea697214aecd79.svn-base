from fabric.api import run

def host_type():
    run('uname -s') #imprime el nombre del kernel
	
#------------------------------------------------------
#Una vez que se define una tarea, se puede ejecutar en uno o más servidores, así:
#------------------------------------------------------
$ fab -H localhost,linuxbox host_type
[localhost] run: uname -s
[localhost] out: Darwin
[linuxbox] run: uname -s
[linuxbox] out: Linux

Done.
Disconnecting from localhost... done.
Disconnecting from linuxbox... done.
#------------------------------------------------------
#------------------------------------------------------
#------------------------------------------------------
#------------------------------------------------------
#------------------------------------------------------
