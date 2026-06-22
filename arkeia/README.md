# Presentación ArkeIA

Deck web construido con el enfoque de
[`zarazhangrui/frontend-slides`](https://github.com/zarazhangrui/frontend-slides).

La presentación contiene 18 diapositivas y toma como fuente principal
`presentacion/src/tesis.pdf` para el problema, estado del arte, marco teórico,
criterios tecnológicos y metodología. También integra evidencia y avances de
los repositorios que componen el ecosistema ArkeIA.

## Demostración

- Simulación pública: <http://eduardoguev.me/Tesis/>
- Código de la simulación:
  <https://github.com/eduardo202020/Tesis/tree/main/tesis/simulacion>

## Abrir

```bash
cd /home/eduardo/proyectos/iot/museiq/presentacion/arkeia
python3 -m http.server 4173
```

Luego abre:

```text
http://127.0.0.1:4173
```

## Controles

- `←` / `→`, `Page Up` / `Page Down` o espacio para navegar.
- Deslizar horizontalmente para navegar en pantalla táctil.
- `E` para activar la edición directa de textos.
- `Ctrl+S` para guardar la edición en el navegador.

## Identidad

La marca pública del proyecto es **ArkeIA** y su lema es
**El pasado cobra vida**.

Los nombres `museiqApp`, `MuseRAG`, `Muse3D`, `iot-museiq` y
`museiq-cultural-video-mvp` se mantienen en la presentación cuando se refieren
a repositorios o módulos técnicos existentes.

Los dos videos incluidos fueron renderizados antes de la migración de marca.
El deck superpone el identificador ArkeIA, pero conviene volver a renderizarlos
desde el generador cultural para sustituir también textos y narración internos.
