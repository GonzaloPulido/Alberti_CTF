# Archivo disfrazado
Tema: Esteganografia / Forense

## 1. Cambio de formato

Flag: **flag{1t_R34Lly_W45nT_4_TxT}**

Cambiamos el formato de la imagen renombrandola. De PNG a TXT.


![Cambio formato](/img/Reto3_1.png)

Este txt es el que tendra el usuario.

Al abrirlo vera que da un error. 

## Ver encabezado

Si usa una herramienta como [Hexed](https://hexed.it/), comprobara que el encabezado es de un PNG.

![Encabezado](/img/Reto3_2.png)


Solo tendra que cambiar el formato de TXT a PNG y ya tendra la imagen con la flag.



