# Sitio de usuario: `lizetortega.github.io`

Esta carpeta contiene **todo lo necesario** para el repositorio de GitHub que publica en **`https://lizetortega.github.io`**.

## Requisito de GitHub

| Usuario GitHub | Nombre del repositorio | URL del sitio |
|----------------|-------------------------|---------------|
| `lizetortega` | `lizetortega.github.io` | `https://lizetortega.github.io` |

## Opción A — Automático (recomendado)

En la carpeta raíz del repo **AgendaT**, ejecuta en PowerShell:

```powershell
.\scripts\crear-repo-github-io.ps1
```

El script copia estos archivos a una carpeta hermana `lizetortega.github.io`, hace `git init`, primer commit y te indica los dos comandos que faltan: crear el repo vacío en GitHub (si no existe) y `git push`.

## Opción B — Manual

1. Crea en GitHub el repo **público** llamado `lizetortega.github.io` (sin README).
2. Copia **todo** el contenido de esta carpeta a la **raíz** de ese repositorio.
3. Push a `main`. En **Settings → Pages** elige **GitHub Actions**.
4. En Meta agrega el dominio `lizetortega.github.io` y verifica (meta tag en `index.html`).

## Meta

Sustituye `YOUR_META_VERIFICATION_CODE` en `index.html` por el código que te da Meta antes de verificar.
