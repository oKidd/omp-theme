# Oh My Posh oKidd Theme

Este tema de Oh My Posh está basado en el tema Bubbles pero ha sido mejorado con características adicionales y un diseño minimalista.

![Preview](https://i.imgur.com/YF0mlx7.png)

## Características

- **Apariencia de diamante** para todos los segmentos.
- **Información del Git**: muestra la rama y el estado del repositorio.
- **Soporte para múltiples lenguajes**: Go, Node.js, Ruby, Java, Julia, PHP y Python.
- **Hora y fecha** del prompt.
- **Usuario** y ms de ejecución en el prompt izquierdo.

## Importante:
*Modificar el perfil de PowerShell para desactivar el prompt del entorno virtual**:
   - Abre tu perfil de PowerShell:
     ```powershell
     notepad $PROFILE
     ```
   - Agrega la siguiente línea para desactivar el prompt del entorno virtual de Python:
     ```powershell
     $env:VIRTUAL_ENV_DISABLE_PROMPT = 1
     ```
