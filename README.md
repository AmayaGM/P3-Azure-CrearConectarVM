# Practica 3 con "VM"

*Crear una maquina virtual*

**Paso 1 _Maquina virtual_**
- Poner en la barra de busqueda "Virtual Machine" y elegir la opcion de maquinas viruales.
![Paso 1](/imagenes/img1.png)

**Paso 2 _Crear VM_**
- Primero debemos elegir el boton "Crear" y elegir la primera opcion
![Paso 2](/imagenes/img2.png)

- Ir a datos basicos
  ![Paso 2.1](/imagenes/im_2.png)

  - Debemos elegir en detalles del proyecto:
      - La suscripcion
      - El grupo de recursos previamente creado
      ![Paso 2.1.1](/imagenes/img2_1.png)

  - Debemos elegir en detalles de instancia:
      - Nombre con el que queremos llamar la maquina virtual
      - La region donde deseamos crearla
      - Guardar el sistema operativo con el que deseamos trabajar la VM
      - Las zonas de disponibilidad
      ![Paso 2.1.2](/imagenes/img2_2.png)

  - Debemos elegir en la cuenta de administrador:
      - Nombre del usuario
      - Contraseña
      - Confirmar contraseña
      ![Paso 2.1.3](/imagenes/img2_3.png)

  - Debemos configurar en Reglas de puerta de entrada:
      - Puertos de entrada publicos
      - Seleccionar puertos de entrada
      ![Paso 2.1.4](/imagenes/img2_4.png)

- Ir a revisar y crear
  ![Paso 2.2](/imagenes/img2_5.png)

- Dar en crear
  ![Paso 2.3](/imagenes/img2_6.png)

- Maquina creada
  ![Paso 2.3](/imagenes/img2_7.png)

- Crear otra VM siguiendo los pasos anteriores (Es necesario que este en la misma red virtual que la anterior)
  ![Paso 2.4](/imagenes/img2_8.png)
      

**Paso 3 Abrir VM en mi equipo**
- Ir al grp de recurso
![Paso 3](/imagenes/img3.png)

  - Entrar a alguna VM
    ![Paso 3.1](/imagenes/img3-1.png)

  - Elegir conectar y RDP
    ![Paso 3.2](/imagenes/img3_2.png)

  - Descargar RDP
    ![Paso 3.3](/imagenes/img3-2.png) 

NOTA: Si estamos en un Equipo windows es necesario descargar "Escritorio remoto de Microsoft" ![Paso 3.4](/imagenes/img3_3.png) 

   - Abrir el archivo y poner las credenciales establecidas en el paso 2 "cuenta de administrador"
    ![Paso 3.5](/imagenes/img3_4.png) 
    ![Paso 3.6](/imagenes/img3_5.png) 

  - Para corroborar las maquinas conectadas nos vamos al apartado redes y vamos a "NuevoGRP-vnet/default"
  ![Paso 3.7](/imagenes/img3_6.png)

  - Luego damos en "dispositivos conectados" y podremos ver los que estan en nuestra red
  ![Paso 3.8](/imagenes/img3_7.png) 
  


**Paso 4 Conectar VM**
- Abrir CMD y teclear "ping" seguido del ip de la maquina a la cual queremos conectarnos
![Paso 4.1](/imagenes/img4.png)
![Paso 4.2](/imagenes/img3_8.png)

**Paso 5 Maquinas conectadas**
![Paso 5](/imagenes/img5.png)
