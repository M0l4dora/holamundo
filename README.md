# Proyecto `holamundo` — Actividad 2: El Taller del Programador

Materia: Laboratorio de Programación (LPR) — E.E.S.T. N.º 1 "Eduardo Ader", Vicente López.
Curso: 5.º año, 3.º división, grupos A-B. Profesor: Mansilla Muñoz York Elías.
Estudiante: Julian Fricker. Año: 2026.

## 1. Entorno configurado

- **Editor:** Visual Studio Code (VS Code), descargado desde el sitio oficial.
- **Extensiones instaladas en esta PC** (`code --list-extensions --show-versions`):
  - `ms-vscode.cpptools@1.35.6` — C/C++ (Microsoft): resaltado de sintaxis, IntelliSense y depuración.
  - `github.copilot@1.372.0` y `github.copilot-chat@0.25.1` — asistencia de IA.
  - `platformio.platformio-ide@3.3.4` — entorno para sistemas embebidos.
- **Extensiones recomendadas por la actividad** (instalar si faltan): C/C++ Extension Pack y Code Runner.
- **Compilador:** MinGW-w64 (GCC), presente en el `PATH` del sistema (verificar con `g++ --version`).
  Si el equipo no permite instalar MSYS2/MinGW, se usa **OnlineGDB** para compilar y ejecutar en la nube.
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

## 4. Estado de las evidencias

Las imágenes de la carpeta `capturas/` son **marcadores de lugar**: reemplazalas por
capturas reales de tu entorno antes de subir el repositorio a GitHub.

- `gpp_version.png`: captura de la consola mostrando la versión de `g++`.
  Si no hay compilador local, documentá el uso de OnlineGDB en el informe.
- `extensiones_vscode.png`: captura del panel de extensiones (`Ctrl + Shift + X`).
- `ejecucion_hola_mundo.png`: captura de la terminal compilando y corriendo el programa.

## 5. Entrega

- Informe en PDF con formato APA 7: `docs/InformeProyectoholamundo.pdf`.
- Repositorio de GitHub con esta misma estructura de carpetas (sin carpetas sueltas).
- Fecha de entrega: prorrogada hasta el 31 de agosto de 2026.
