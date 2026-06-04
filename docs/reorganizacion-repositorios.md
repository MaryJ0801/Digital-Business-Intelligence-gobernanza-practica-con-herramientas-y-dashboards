# Reorganización profesional del portafolio

## Diagnóstico breve

Antes de la reorganización, el trabajo del curso estaba distribuido en varios repositorios públicos independientes:

- `Digital-Business-Intelligence-gobernanza-practica-con-herramientas-y-dashboards`
- `AlineamientoDinamicoHuawei`
- `CulturaLiderazgoDigital`
- `PortafolioDatos`
- `tutor-comex-utn`
- `merceologia-ai-dbi-portfolio`

El problema principal era que los entregables del curso quedaban dispersos, lo que hacía más difícil revisar la evolución académica completa, entender la relación con los 6 Pivotes de la Evolución Digital y navegar los productos desde un único portafolio central.

## Objetivo de la reorganización

Consolidar el repositorio `Digital-Business-Intelligence-gobernanza-practica-con-herramientas-y-dashboards` como portafolio central del curso Digital Business Intelligence de INCAE Business School, integrando dentro de él los repositorios secundarios relacionados con las semanas y productos del curso.

## Estructura final propuesta

```text
.
├── index.html
├── README.md
├── docs/
│   └── reorganizacion-repositorios.md
├── Semana02/
│   ├── index.html
│   └── README.md
├── Semana03/
│   ├── index.html
│   └── README.md
├── RAPS_myRAzept/
│   └── index.html
├── Semana05/
│   ├── index.html
│   └── README.md
├── PortafolioDatos/
│   ├── index.html
│   ├── styles.css
│   ├── script.js
│   └── RAPS_myRAzept/
└── data-product-1/
```

## Integraciones realizadas

| Repositorio original | Nueva ubicación | Estado |
| --- | --- | --- |
| `AlineamientoDinamicoHuawei` | `Semana02/` | Integrado |
| `CulturaLiderazgoDigital` | `Semana03/` | Integrado |
| `PortafolioDatos` | `PortafolioDatos/` | Integrado |

Cada repositorio secundario conserva un README con aviso de migración hacia el portafolio central, para evitar confusión mientras se decide si se archiva o elimina.

## Mapeo académico por semana

| Semana | Enfoque | Pivote | Entregable |
| --- | --- | --- | --- |
| Semana 01 | Creación del portafolio | Base del portafolio | Portada central en GitHub Pages |
| Semana 02 | Alineamiento dinámico | Pivote 1 | Dashboard Huawei |
| Semana 03 | Cultura y liderazgo digital | Pivote 2 | Dashboard FCC |
| Semana 04 | Innovación centrada en el cliente | Pivote 3 | RAPS GmbH / myRAzept |
| Semanas 05 a 07 | Agilidad operativa, acceso y uso de datos, ecosistemas colaborativos | Pivotes 4, 5 y 6 | Asistente Académico COMEX UTN |

## Repositorios que deben permanecer

La estructura pública recomendada después de la consolidación es:

1. `Digital-Business-Intelligence-gobernanza-practica-con-herramientas-y-dashboards`
2. `tutor-comex-utn`
3. `merceologia-ai-dbi-portfolio`

## Repositorios candidatos a archivar

Después de verificar que el portafolio central funciona correctamente, estos repositorios pueden archivarse:

- `AlineamientoDinamicoHuawei`
- `CulturaLiderazgoDigital`
- `PortafolioDatos`

No se recomienda eliminarlos inmediatamente. Primero conviene archivarlos para preservar historial, evidencias y trazabilidad.

## Pasos manuales recomendados en GitHub

1. Abrir el portafolio central publicado en GitHub Pages.
2. Probar los enlaces internos:
   - `/Semana02/`
   - `/Semana03/`
   - `/RAPS_myRAzept/`
   - `/Semana05/`
   - `/PortafolioDatos/`
3. Confirmar que cada repositorio secundario muestra el aviso de migración.
4. Ir a cada repositorio secundario candidato.
5. Entrar a `Settings`.
6. En la zona de administración del repositorio, seleccionar `Archive this repository`.
7. Confirmar el archivado.

## Recomendaciones profesionales

- Mantener el README principal como índice ejecutivo.
- Evitar duplicar proyectos como repos independientes si ya viven dentro del portafolio central.
- Usar nombres de carpetas consistentes y comprensibles.
- Conservar evidencia técnica, dashboards y páginas HTML dentro de carpetas por semana.
- Mantener `tutor-comex-utn` como repositorio independiente porque corresponde a la app publicada.
- No borrar repositorios hasta que el profesor o evaluador haya revisado la versión consolidada.
