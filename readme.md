# MinervaOS - AOSP Made with :heart: & :coffee: by students of the UES
<p align="center">
  <img src="https://avatars0.githubusercontent.com/u/39605972">
</p>

## Instrucciones de inicializacion
* Para comenzar con Android/MinervaOS, debes de estar familiarizado con [Git y Repo](https://source.android.com/source/using-repo.html).

* Luego sera necesario obtener una copia completa del codigo fuente, para ello use el siguiente comando:

      repo init -u git://github.com/MinervaOS/android.git -b mos-1.0 -g all,-notdefault,-darwin

* Luego debera sincronizar su copia local con este repositorio:

      repo sync --force-sync

La descarga puede tomar entre 1-20 horas, dependiendo de su velocidad de intenet, tenga paciencia

## Instrucciones para compilar
* Para compilar MinervaOS primero debe inicializar el ambiente de trabajo, use el siguiente comando:

      source build/envsetup.sh

* Ahora inicialize el dispositivo a compilar, para ello debe de seleccionar entre la lista de dispositivos compatibles.

      breakfast

* Seleccione el numero de su dispositivo y presione enter.

* Por ultimo ingrese el comando para iniciar el proceso:

      brunch

El proceso puede tardar entre 40-500 minutos dependiendo de la potencia de su computadora, tenga paciencia.

Al finalizar usted encontrara el archivo de instalacion en:

     out/target/product/{device_code_name}/MinervaOS-*.zip
