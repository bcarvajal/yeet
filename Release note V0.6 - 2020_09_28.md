# Release note V0.6 - 2020/09/28

# Nuevas Funcionalidades

- **[Modulo de Indicadores / GetoRemoteData]:**
  - SiteCard App: Creación de modulos para carptura de Indicadores:
    - **Nyha**
    - **Had**
    - **EHFScB**
    - ** DHFKS**
  - SiteCard Web: Vista de Indicadores capturados.
- **[Modulo Ficha Virtual Gym/ GetoRemoteData]:**
  - Sitecard Web: Incorporo modulo para extracción de datos de fichas físicas de gimnasio, carga y despliegue de datos.
  - Edición solo esta disponible para perfil de tipo Kinesiólogo y despliegue para todos los perfiles de profesionales.

# Fixes

- Corrección de Typos y ortografía.
- Optimización de modelo de Datos.

# Improvements

- Mejoras en interfaces y despliegue.
- Actualización de package.
- Corrección al modelo de Datos.

# Problemas abiertos

- Se necesita condensar toda la data de indicadores en una única Vista.
- Se requiere modificar la sincronización entre App y Web para que sea directa y no por un intermediario.
- Existen algunos indicadores sin información explicita en el documento (reporte en construcción), hay data faltante para algunos indicadores.
  - **SHFM**
  - **Hearth Risk Calculator**
  - **MHLFQS**
- Arreglar calculo de indicadores según documento.
  - **Had**
  - **EHFScB**
