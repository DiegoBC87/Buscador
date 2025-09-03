
Web App: Buscar Placas y Teléfonos (Voltosas)
-------------------------------------------

Qué contiene este paquete:
- index.html : la aplicación web que carga el Excel desde OneDrive/SharePoint o desde un archivo local.
- README.txt  : instrucciones rápidas.

Instrucciones rápidas:
1) Descarga este ZIP y descomprímelo.
2) Abre index.html en el navegador (doble clic). Si vas a usar un enlace compartido de OneDrive/SharePoint,
   pégalo en el campo "Pega aquí el enlace compartido" y pulsa "Cargar desde enlace".
   - Nota: algunos enlaces de OneDrive/SharePoint no permiten descarga directa por razones de permisos o CORS.
     Si la carga por enlace falla, usa el botón de subir archivo para seleccionar tu BD_Vehiculos.xlsx.
3) Una vez cargados los datos, escribe Teléfono o Placa y pulsa Buscar.
4) Pulsa Limpiar para ver todos los registros otra vez.

Consejos para que la carga por URL funcione:
- En OneDrive/SharePoint, cuando generes el enlace, selecciona "Cualquiera con el vínculo" y permite la descarga.
- Si el enlace sigue fallando por CORS, usa la opción de subir archivo o hospeda el Excel en un servidor que permita
  requests desde navegadores (o usa un pequeño backend - puedo ayudarte a desplegar uno si lo necesitas).
