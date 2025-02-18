Rama windowExe: Ejecutable para window app: PracticaExe.exe
Rama linux:  Ejecutable dentro de dist: Practica.exe


## Comandos necesarios en linux


1. creamos un entorno virtual
  python -m venv venv
2. lo activamos
   source venv/bin/activate
3. instalamos el pyinstaller
  pip install pyinstaller
4.  instalamos el pyqt5 tools
   pip install pyqt5-tools
5.  convertimos las images.qrc a images_rc.py
  pyrcc5 images.qrc -o images_rc.py
6. crear el ejecutable
  pyinstaller -onefile practicaExe.py
7.  vamos a la carpeta dist
  cd dist
8. Ejecutamos el output
   ./practicaExe
# te pase el dist por google drive
https://drive.google.com/file/d/1QofoRD_jbpmTWYooI5heROcVl5ldGAJo/view?usp=drive_link


# drive para el windows
https://drive.google.com/file/d/1wfJJ-ZQNbwqQlb5asDyN1A1cRk_XCLIo/view?usp=drive_link
