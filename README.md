# Proyecto `holamundo` — Actividad 2: El Taller del Programador

Materia: Laboratorio de Programación (LPR) — E.E.S.T. N.º 1 "Eduardo Ader", Vicente López.
Curso: 5.º año, 3.º división, grupos A-B. Profesor: Mansilla Muñoz York Elías.
Estudiante: Julian Fricker. Año: 2026.

## 1. Entorno configurado

- **Editor:** Visual Studio Code (VS Code), descargado desde el sitio oficial.
- **Extensiones instaladas en esta PC** (`code --list-extensions --show-versions`):
  - `ms-vscode.cpptools@1.35.6` — C/C++ (Microsoft): resaltado de sintaxis, IntelliSense y depuración.
  - `ms-vscode.cpptools-extension-pack@1.5.1`, `ms-vscode.cmake-tools@1.25.10` y `ms-vscode.cpptools-themes@2.0.0`.
  - `github.copilot@1.372.0` y `github.copilot-chat@0.25.1` — asistencia de IA.
  - `platformio.platformio-ide@3.3.4` — entorno para sistemas embebidos.
  - Opcional: instalar Code Runner para ejecutar con un clic.
- **Compilador:** MSYS2 + MinGW-w64 GCC 16.2.0, instalado en `C:\msys64\mingw64\bin\g++.exe` y agregado al `PATH` del usuario. Verificar con `g++ --version`.
  La configuración de IntelliSense está en `.vscode/c_cpp_properties.json` (carpeta ignorada por Git).
  Si otro equipo no permite instalar MSYS2, la alternativa es **OnlineGDB**.
- **Terminal:** terminal integrada de VS Code (`Ctrl + Ñ`) en PowerShell sobre Windows 10/11.

## 2. Estructura del repositorio

```
holamundo/
├── .gitignore              # Ignora .vscode/ y binarios generados
├── README.md               # Este archivo
├── LICENSE                 # Licencia breve de uso educativo
├── docs/
│   ├── InformeProyectoholamundo.pdf   # Entregable en formato APA 7
│   └── InformeProyectoholamundo.docx  # Fuente editable del informe
├── src/
│   └── main.cpp            # Primer programa de prueba en C++
└── capturas/
    ├── gpp_version.png              # Evidencia de `g++ --version`
    ├── extensiones_vscode.png       # Evidencia de las extensiones instaladas
    └── ejecucion_hola_mundo.png     # Evidencia de la compilación y ejecución
```

## 3. Compilación y ejecución

Desde la raíz de la carpeta `holamundo`, en la terminal de VS Code:

```powershell
g++ src/main.cpp -o src/holamundo.exe
.\src\holamundo.exe
```

Salida esperada:

```
=====================================================
  Hola Mundo! Bienvenido al Taller de LPR 2026.
  Estudiante: Julian Fricker
=====================================================
```

## 4. Evidencias

Las imágenes de `capturas/` muestran la salida real obtenida en esta PC:

- `gpp_version.png`: salida de `g++ --version` (GCC 16.2.0, MSYS2).
- `extensiones_vscode.png`: salida de `code --list-extensions --show-versions`.
- `ejecucion_hola_mundo.png`: comandos de compilación y salida del programa.

Si querés, reemplazalas por capturas de pantalla de tu propia sesión de VS Code.

## 5. Entrega

- Informe en PDF con formato APA 7: `docs/InformeProyectoholamundo.pdf`.
- Repositorio de GitHub con esta misma estructura de carpetas (sin carpetas sueltas).
- Fecha de entrega: prorrogada hasta el 31 de agosto de 2026.
