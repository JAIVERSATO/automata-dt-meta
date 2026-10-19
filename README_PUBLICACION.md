# PUBLICACIÓN EN GITHUB PAGES — AUTÓMATA DT META

## Contenido
Este paquete contiene dos fuentes públicas HTTPS para Microsoft Copilot Agent Builder:

1. `/manual/` — Manual Maestro del Autómata.
2. `/catalogo/` — Catálogo operativo generado a partir de `automata_pqrsd_dt_meta_v4.xlsx`.

No se publicaron las hojas históricas de radicados, bases de datos de casos ni registros ciudadanos.

## Advertencia
GitHub Pages es público. El Catálogo Operativo sí contiene nombres de funcionarios y reglas internas de reparto tomadas del archivo fuente. Valide previamente que su publicación pública esté autorizada por la entidad.

## Pasos
1. Cree una cuenta o ingrese a GitHub.
2. Cree un repositorio nuevo llamado `automata-dt-meta`.
3. Suba TODO el contenido de esta carpeta a la raíz del repositorio.
4. Abra `Settings` > `Pages`.
5. En `Build and deployment`, seleccione `Deploy from a branch`.
6. Seleccione la rama `main` y la carpeta `/ (root)`.
7. Guarde y espere a que GitHub muestre la URL publicada.
8. Verifique en una ventana privada que estas rutas abran sin iniciar sesión:
   - `https://TUUSUARIO.github.io/automata-dt-meta/manual/`
   - `https://TUUSUARIO.github.io/automata-dt-meta/catalogo/`
9. Pegue únicamente esas dos URLs en el conocimiento del agente.

## Instrucción breve sugerida para Agent Builder
Eres el Autómata de Análisis y Reparto de la Dirección Territorial Meta del Ministerio del Trabajo.

Antes de clasificar, determinar competencia o repartir una actuación, consulta obligatoriamente las fuentes `Manual Maestro — Autómata DT Meta` y `Catálogo Operativo — Autómata DT Meta`.

Las combinaciones Tipo PQRSD, Tema y Subtema deben coincidir literalmente con el Catálogo Operativo. Las reglas de análisis, competencia territorial, reparto y salida deben aplicarse conforme al Manual Maestro.

No inventes datos ni completes información no verificable. Cuando una decisión no pueda comprobarse con las fuentes o existan contradicciones, utiliza `REVISIÓN MANUAL` e indica brevemente la causa en el resumen.

La salida debe contener únicamente `Resumen` y `Matriz para Excel`.
