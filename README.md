# Diseño de un Modelo de Red Educativa Segura y Sostenible

## Descripción

Este repositorio contiene los archivos del proyecto académico **Diseño de un Modelo de Red Educativa Segura y Sostenible**, desarrollado mediante un entorno de simulación con GNS3 y FortiGate.

El proyecto propone una arquitectura de red orientada a entornos educativos, con el propósito de mejorar la segmentación de los usuarios, fortalecer los mecanismos de seguridad, administrar el tráfico de red y establecer comunicaciones seguras entre diferentes sedes.

El laboratorio permite visualizar y revisar la topología diseñada, las configuraciones de los dispositivos, los mecanismos de seguridad implementados y las pruebas funcionales realizadas durante el desarrollo del proyecto.

## Objetivos

- Diseñar una arquitectura de red segmentada para un entorno educativo.
- Implementar controles de seguridad y políticas de acceso mediante FortiGate.
- Regular y administrar el tráfico de red.
- Establecer conectividad segura entre sedes mediante VPN IPsec Site-to-Site.
- Validar las funcionalidades implementadas mediante pruebas en un ambiente simulado.
- Documentar el diseño, las configuraciones y los resultados obtenidos.

## Tecnologías utilizadas

| Tecnología | Descripción |
|---|---|
| GNS3 | Diseño y simulación de la topología de red. |
| FortiGate | Firewall, segmentación, políticas de seguridad y VPN. |
| VMware | Plataforma de virtualización utilizada para el entorno de laboratorio. |

## Funcionalidades del laboratorio

- Segmentación de red mediante VLAN.
- Políticas de firewall y control de acceso.
- Web Filter.
- Application Control.
- Autenticación y portal cautivo.
- Traffic Shaping.
- VPN Site-to-Site IPsec.
- Conectividad y validación entre redes.
- Pruebas de políticas de seguridad y tráfico.

## Estructura del repositorio

- `gns3-project/`: archivos del proyecto de simulación.
- `backups/`: configuraciones sanitizadas de los FortiGate.
- `documentation/`: documentación técnica y procedimientos.
- `evidence/`: capturas y evidencias de las pruebas realizadas.
- `diagrams/`: diagramas de la topología y arquitectura.

## Requisitos

Para utilizar el proyecto se requiere:

- GNS3 instalado y configurado.
- VMware, cuando sea necesario para el entorno de virtualización.
- Appliances e imágenes compatibles con los dispositivos utilizados en el proyecto.
- Recursos de CPU, RAM y almacenamiento suficientes para ejecutar la topología.
- Licencias correspondientes, cuando las funcionalidades utilizadas lo requieran.

## Uso del proyecto

1. Descargar o clonar este repositorio.
2. Importar o abrir el proyecto de GNS3.
3. Instalar y asociar los appliances requeridos, si no están disponibles.
4. Revisar la documentación y el direccionamiento de red.
5. Iniciar los dispositivos y realizar las pruebas siguiendo los procedimientos documentados.

## Limitaciones

El proyecto fue desarrollado en un ambiente simulado y estuvo sujeto a las limitaciones de las licencias y funcionalidades disponibles en FortiGate. Por lo tanto, algunos comportamientos pueden variar respecto a una implementación en infraestructura física o con licenciamiento completo.

## Propósito académico

Este proyecto fue desarrollado con fines académicos, de aprendizaje y demostración técnica en el área de redes y ciberseguridad. Los archivos y configuraciones se comparten como referencia para el estudio y la reproducción del laboratorio, respetando las licencias de los componentes utilizados.

Se recomienda revisar las configuraciones antes de utilizarlas en cualquier entorno real.
