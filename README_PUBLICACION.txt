# Microsite Erasmus+ IES Castelar

Este paquete contiene una propuesta de microsite estático para enlazar desde la web oficial del IES Castelar.

## Archivos principales
- `index.html`: página principal.
- `assets/styles.css`: estilos de la página.
- `assets/escudo-castelar.jpg`: escudo del centro.
- `assets/cofinanciado-ue.png`: imagen de cofinanciación europea.
- `documentos/`: documentos DOCX adaptados al IES Castelar.

## Cómo publicarlo en la web del centro
1. Descomprimir este ZIP.
2. Subir la carpeta completa a la web del centro, por ejemplo como `/erasmus/`.
3. Crear un enlace desde el menú de la web oficial con el texto `Erasmus+`.
4. El enlace debería apuntar a la ruta donde se haya subido `index.html`, por ejemplo: `https://iescastelar.educarex.es/erasmus/`.

## Si se usa Google Sites
Google Sites no importa directamente HTML completo como una web normal. En ese caso:
1. Crear un nuevo Google Sites llamado `Erasmus+ IES Castelar`.
2. Copiar los bloques de contenido de `index.html` manualmente.
3. Subir los documentos DOCX a Drive o a la web del centro.
4. Sustituir los enlaces de la sección Documentos por los enlaces definitivos.
5. Publicar el Google Sites y enlazarlo desde la web oficial del centro.

## Pendiente antes de publicar
- Completar nombre de la persona coordinadora Erasmus+.
- Completar correo específico Erasmus+, si existe.
- Sustituir o añadir el enlace al formulario de solicitud.
- Revisar si el centro quiere publicar sólo SCH o también apartados específicos para FP/VET/HED.
- Revisar fechas y número de plazas de cada convocatoria antes de activar enlaces públicos.


ACTUALIZACIÓN AÑADIDA
---------------------
Se ha incorporado un nuevo apartado en la página principal:
"Movilidades realizadas este curso".

Este apartado resume los proyectos y movilidades recogidos en la presentación:
- KA220 AI4GREENED.
- KA121-SCH.
- KA121-VET.
- KA131-HED.

También se han añadido dos archivos a la carpeta /documentos:
- proyectos-erasmus-ies-castelar.pdf
- proyectos-erasmus-ies-castelar.pptx

ACTUALIZACIÓN AÑADIDA - MAPA DE MOVILIDADES
------------------------------------------
Se ha incorporado un apartado llamado "Mapa de movilidades".
Incluye un mapa esquemático de Europa con destinos históricos y destinos de este curso:
- Proyectos anteriores: Build a Bridge, Past Roads and Future Ways, BOOST.
- Curso actual: AI4GREENED, KA121-SCH, KA121-VET y KA131-HED.

El mapa está hecho en HTML/CSS/SVG, por lo que no depende de Google Maps ni de servicios externos.
Puede publicarse directamente junto con el resto del microsite.


Actualización del mapa:
- Se ha incorporado un mapa grande de Europa, con contorno geográfico reconocible, marcadores por destino y recuadro lateral para Martinica.
- El mapa está incluido como imagen local en assets/mapa-movilidades-castelar.png, por lo que no depende de servicios externos.
