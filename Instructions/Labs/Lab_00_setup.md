# Seguimiento del uso de datos de ejemplo con Microsoft 365 Copilot

En el resto de laboratorios, crearemos indicaciones para Microsoft 365 Copilot que hagan referencia a los archivos siguientes:

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

Para asegurar que Microsoft 365 Copilot puede acceder a estos archivos más adelante, primero los cargaremos en OneDrive.

## Cargar archivos en OneDrive

Sigue los pasos siguientes para cargar todos los archivos necesarios en **OneDrive**:

1. Inicia sesión en la máquina virtual proporcionada por el proveedor de inquilinos con la cuenta de **administrador** local con la contraseña `Pa55w.rd`.

2. En la barra de tareas de Windows, selecciona **Microsoft Edge**.

3. En la barra de direcciones, escribe `https://onedrive.live.com/login`.

4. En **Bienvenido a Microsoft 365**, selecciona **Iniciar sesión**.

5. En la **solicitud de inicio de sesión**, escribe userx@yourtenant.onmicrosoft.com (proporcionado por el proveedor de inquilinos) y selecciona **Siguiente**.

6. En la pantalla **Escribir contraseña**, escribe la contraseña 1 (proporcionada por el proveedor de inquilinos) y selecciona **Iniciar sesión**.

7. Si se te pide **Mantener la sesión iniciada**, selecciona **No volver a mostrar** y **Sí**.

8. En **OneDrive**, en la esquina superior izquierda, selecciona **+** (agregar nuevo) > **Carga de archivo**.

    ![Captura de pantalla de Agregar nuevo archivo](../Labs/Media/add_new.png)

9. En **Explorador de archivos**, selecciona **Este equipo** > ** Disco local (C:)** y abre la carpeta **ResourceFiles**.

10. Selecciona todos los archivos de la carpeta **ResourceFiles** y, después, selecciona **Abrir** para cargarlos en **OneDrive**.

11. Una vez completada la carga, deberías ver **Se han cargado 29 elementos en Mis archivos** en el centro inferior de la pantalla.

12. Deja **Edge** abierto y ve a la siguiente tarea.

### Hacer referencia a archivos

Al hacer referencia a archivos de Copilot, es posible que no encuentres algunos archivos de las sugerencias proporcionadas. Esto ocurre porque ciertas experiencias de Copilot solo hacen referencia a archivos de la lista de utilizados recientemente, mientras que otros permiten examinar OneDrive directamente. Agregarlos a esa lista es tan fácil como abrirlos en la aplicación adecuada de Microsoft 365.  Una vez que se hayan abierto, deben aparecer en la lista de utilizado recientemente.

> [!IMPORTANT]
> Microsoft 365 Copilot solo funcionará con archivos guardados en OneDrive. Los archivos almacenados localmente en el equipo deberán moverse a OneDrive para activar Copilot.

A medida que avances, tendrás la oportunidad de probar otras indicaciones en estos archivos y se recomienda que lo hagas para explorar y mejorar tus habilidades.
