# Proy-ADS-I

Proyecto de análisis y diseño de un sistema para la programación y ejecución de subastas de inmuebles. Reúne modelos UML, documentación de requisitos y prototipos de interfaces.

## Procesos modelados

- Registro de inmuebles y programación de subastas públicas.
- Generación de bases, expedientes e informes.
- Presentación de propuestas y aprobaciones.
- Formalización de la adjudicación y del contrato.
- Gestión de la entrega del inmueble.

## Herramientas y formatos

- **IBM Rational Rhapsody:** modelos de negocio, actores, entidades, realizaciones y casos de uso.
- **Word o un visor compatible:** documentación en `.docx`.
- **Excel o un visor compatible:** matriz de actividades y requisitos en `.xlsx`.
- **Imágenes JPG:** prototipos de las pantallas del sistema.

## Estructura

| Archivo o carpeta | Contenido |
| --- | --- |
| `ProyectoRhapsody/CasoProyecto/CasoProyecto.rpyx` | Archivo principal del proyecto UML. |
| `ProyectoRhapsody/CasoProyecto/CasoProyecto_rpy/` | Paquetes y modelos del sistema y del negocio. |
| `ProyectoRhapsody/BusinessModelingProfile/` | Perfil de modelado de negocio. |
| `Guis_Sistema/` | Prototipos de registro de inmuebles, programación de subastas, bases y entrega. |
| `Especificación de Software.docx` | Documento de especificación de software. |
| `Plantilla-Modelamiento de Negocio.docx` | Documento de modelado de negocio. |
| `Matriz_Actividades-Req.xlsx` | Matriz de actividades y requisitos. |

## Cómo revisar el proyecto

```bash
git clone https://github.com/thoonidev/Proy-ADS-I.git
cd Proy-ADS-I
```

1. Abre `ProyectoRhapsody/CasoProyecto/CasoProyecto.rpyx` con una versión compatible de Rhapsody.
2. Conserva la estructura de carpetas para mantener las referencias de los modelos.
3. Si se solicita el perfil de negocio desde una ruta antigua del equipo original, vincúlalo a `ProyectoRhapsody/BusinessModelingProfile/`.
4. Consulta los documentos y la matriz, y revisa las imágenes de `Guis_Sistema/` como referencia de las interfaces propuestas.

## Alcance

El repositorio contiene análisis, diseño y prototipos estáticos. No incluye una aplicación implementada, una base de datos desplegable ni comandos de ejecución de un servidor.
