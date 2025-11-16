Aquí tienes el README con etiquetas/badges de tecnologías estilo colorido y el asesor incluido. Puedes pegarlo tal cual en `README.md`.

```markdown
## 🧠 Algorithms AR — App educativa de Realidad Aumentada

Aplicación desarrollada con Unity para enseñar algoritmos de ordenamiento (Bubble, Selection, Insertion) mediante experiencias interactivas en Realidad Aumentada. Combina teoría paso a paso y prácticas AR con manipulación de objetos, orientada a smartphones (ARCore/ARKit) y preparada para Meta Quest.

### 🏷️ Tecnologías

![Unity 2022.3 LTS](https://img.shields.io/badge/Unity-2022.3_LTS-black?logo=unity)
![URP 14](https://img.shields.io/badge/URP-14.0-blueviolet)
![AR Foundation 5.2](https://img.shields.io/badge/AR_Foundation-5.2.0-1abc9c)
![XR Interaction Toolkit 3.1](https://img.shields.io/badge/XR_Interaction_Toolkit-3.1.2-2ecc71)
![OpenXR Ready](https://img.shields.io/badge/OpenXR-ready-9b59b6?logo=openxr)
![TextMeshPro](https://img.shields.io/badge/TextMeshPro-3.0.9-3498db)
![Android](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/Platform-iOS-000000?logo=apple&logoColor=white)
![Meta Quest (prep)](https://img.shields.io/badge/Meta_Quest-prepared-563d7c)
![License MIT](https://img.shields.io/badge/License-MIT-yellow)

### 🚀 Características
- Modo Teórico: explicaciones guiadas y visualizaciones paso a paso.
- Modo Práctico (AR): cubos numéricos interactivos que ilustran cada algoritmo.
- Catálogo y Niveles: Principiante, Intermedio, Avanzado.
- UI optimizada: Safe Area, Scroll Views, prefabs reutilizables.
- Preparado para OpenXR/Quest sin tocar escenas móviles.

### 🛠️ Requisitos
- Unity Hub + Editor `2022.3.62f1`
- Android SDK/NDK + JDK (Android), Xcode (iOS)
- Opcional: OpenXR activado para Meta Quest

### ▶️ Puesta en marcha
1. Abrir `ARgorithm` en Unity `2022.3.62f1`.
2. Esperar resolución de paquetes.
3. Verificar URP: `Edit > Project Settings > Graphics` → `URP-Performant`.
4. Calidad: `Edit > Project Settings > Quality` → Android/iOS en `Performant`.
5. Quest (opcional): `XR Plug-in Management (Android)` → activar `OpenXR` y “Meta Quest Support”.

### 📦 Estructura
- `Assets/Scenes` — escenas (ej.: `SampleScene.unity`).
- `Assets/MobileARTemplateAssets` — prefabs, materiales, shaders y scripts AR base.
- `Assets/Settings` — `URP-Performant.asset` y renderer.
- `Assets/XR` — `XRGeneralSettings.asset`.
- `Packages/manifest.json` — dependencias.
- `ProjectSettings` — gráficos, calidad, XR.

### 🧭 Flujo de ramas
- `main` (estable), `develop` (integración), `feature/*`, `chore/*`, `fix/*`.
- Ejemplo: `chore/perf-mobile-quality-defaults`
  - Android/iOS → `Performant` por defecto.
  - Se añade `OpenXR` en dependencias.

### 🗺️ Roadmap (resumen)
- Escenas: `SCN_BasicTheory`, `SCN_Difficulty`, `SCN_BeginnerCatalog`.
- Animaciones paso a paso para Bubble/Selection/Insertion.
- UI de catálogo con `ScriptableObjects`.
- Integración avanzada para Meta Quest (opcional).

### 👤 Créditos
- Autores: Miquel De la Piedra, Enrique Llatas  
- Asesor especializado: Elio Navarrete  
- Universidad Peruana de Ciencias Aplicadas (UPC) — Ingeniería de Software

### 🪪 Licencia
MIT. Ver `LICENSE` si aplica.
```
