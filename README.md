# Teleprompter Mauro · Descargas

Este repositorio **solo distribuye los instaladores oficiales** de Teleprompter Mauro mediante
[GitHub Releases](../../releases). No contiene el código fuente de la aplicación.

**Página oficial de descargas:** https://teleprompter-mauro.vercel.app/descargas

Descarga Teleprompter Mauro **solo** desde la página oficial o desde la sección *Releases* de este repositorio.

## Plataformas

| Plataforma | Cómo se instala |
|---|---|
| Web | Abre https://teleprompter-mauro.vercel.app en el navegador |
| iPhone y iPad | Safari → Compartir → **Agregar a pantalla de inicio** |
| Android | APK de esta página, o Chrome → ⋮ → **Instalar app** |
| Mac | DMG (Apple Silicon o Intel) |
| Windows | Instalador EXE o MSI |

## Verificar un archivo descargado

Cada versión publica la suma **SHA-256** de cada instalador. Para comprobar que tu archivo es idéntico al oficial:

- **Mac / Linux:** `shasum -a 256 ARCHIVO`
- **Windows (PowerShell):** `Get-FileHash ARCHIVO -Algorithm SHA256`

La APK de Android está firmada con el certificado oficial de Teleprompter Mauro. Huella SHA-256 del certificado:

```
BC:AF:67:1B:57:45:D5:97:2E:16:E3:00:2E:2B:00:B5:FC:C4:02:A3:6A:71:07:B5:7B:F5:34:C6:CD:88:12:55
```

## Privacidad

Teleprompter Mauro procesa todo en tu dispositivo: tus guiones y videos no se suben a ningún servidor.

© Mauro. Todos los derechos reservados.
