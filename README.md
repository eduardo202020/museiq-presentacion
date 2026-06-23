# Presentación ArkeIA

Repositorio de la presentación web del ecosistema ArkeIA.

## Contenido

- [`arkeia/`](arkeia/): deck interactivo de 18 diapositivas.
- [`src/`](src/): tesis, formato institucional y recursos originales.

## Ejecutar

```bash
cd arkeia
python3 -m http.server 4173
```

Abrir <http://127.0.0.1:4173>.

La demostración funcional del recorrido está disponible en
<http://eduardoguev.me/Tesis/>.

Video del flujo integrado: <https://youtu.be/fwv-_J_4pZA>.

## Pruebas en Windows (PowerShell)

```powershell
cd C:\Users\pc\Documents\proyectos\Museiq\museiq-presentacion\arkeia
py -3.11 -m http.server 4173
```

Abre <http://127.0.0.1:4173>. Usa `Ctrl+C` para cerrar el servidor.
