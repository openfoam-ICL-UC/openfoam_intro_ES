# openfoam_intro_ES

Taller Introducción a OpenFOAM para Ingeniería Química. Los ejemplos son relevantes para ingeniería de procesos, alimentos y biotecnología.

#### Conocimientos previos sugeridos

Los siguientes conocimientos previos facilitarán de enorme manera tu ruta de aprendizaje. Sin embargo, estos no son requisitos absolutos y se pueden aprender en la marcha

* Dominio básico de la consola `Unix`: Si usted quiere aprender lo básico, le recomendamos este curso de Software Carpentry de tres horas en español: [La Terminal de Unix.](https://swcarpentry.github.io/shell-novice-es/)
* Fenómenos de Transporte o Mecánica de Fluidos + Transferencia de Calor/Masa a nivel de pregrado
* Fundamentos básicos de métodos numéricos: Si usted quiere aprender algoritmos básicos para resolver problemas a los valores iniciales, de contorno y de valores iniciales y de contorno en el contexto de Fenómenos de Transporte, le recomendamos el MOOC gratuito [Transferencia de calor, masa y momentum computacional.](https://www.coursera.org/learn/transferencia-de-momentum-calor-y-masa-computacional)

#### Requerimientos computacionales
Los siguientes requerimientos computacionales son **absolutamente necesarios** para iniciar el taller.
Al iniciar el taller, es necesario instalar los siguientes software:

* OpenFOAM v2306: [Instrucciones de instalación]()
* Si su OS es Windows, Windows Subsystem for Linux 2 (WSL 2): [Instrucciones de instalación](https://github.com/openfoam-ICL-UC/openfoam_intro_ES/wiki/Instalaci%C3%B3n-de-OpenFOAM)
* Si su OS es macOS, versión pre-compilada de OpenFOAM en Docker container: [Instrucciones de instalación](https://github.com/openfoam-ICL-UC/openfoam_intro_ES/wiki/Instalaci%C3%B3n-de-OpenFOAM)
* Si su OS es Linux, no es necesario instalar máquinas virtuales o Docker.
* ParaView > 5.0: Se debe instalar en Windows Subsystem for Linux o macOS o Linux: [Instrucciones de instalación](https://github.com/openfoam-ICL-UC/openfoam_intro_ES/wiki/Instalaci%C3%B3n-de-OpenFOAM)

Este taller tiene dos sesiones con dos partes cada una. Los objetivos de aprendizaje de cada parte de este taller son:

#### Sesión 1 Parte 1: Introducción al método de volúmenes finitos
1. Convertir un modelo matemático continuo a un modelo numérico discreto para un problema de transferencia de calor unidimensional no estacionaria.
2. Discretizar ecuaciones diferenciales parciales mediante el método de volúmenes finitos.
3. Implementar algoritmo de solución en Python y comparar discretización y algoritmos para sistemas de ecuaciones lineales.

#### Sesión 1, Parte 2: Implementación de la solución numérica a un problema de fenómenos de transporte en OpenFOAM
1. Configurar un caso de OpenFOAM representativo de la transferencia de calor tridimensional no estacionaria en un sistema de flujo de fluidos.
2. Ejecutar un `solver` de OpenFOAM desde la línea de comando.
3. Visualizar los resultados de la simulación utilizando paraview.

#### Sesión 2, Parte 1: Post-procesamiento de resultados en OpenFOAM
1. Escribir un código `functionObject` para calcular cantidades de interés ingenieril.
2. Generar figuras explicativas de fenómenos de transporte relevantes a partir de filtros de Paraview. 
3. Comparar los resultados del modelo de OpenFOAM con los resultados obtenidos en Python.

#### Sesión 2, Parte 2: Ejemplos y solvers avanzados de OpenFOAM para fenómenos de transporte acoplados
1. Analizar la implementación de las ecuaciones de conservación de calor, masa y cantidad de movimiento para el solver `icoReactingMultiphaseInterFoam`.
2. Reproducir un tutorial de OpenFOAM de evaporación de agua en aire, donde la transferencia de calor y masa están acopladas.
3. Post-procesar un caso multifásico de OpenFOAM.

La documentación asociada a cada sesión puedes encontrarla en [Wikis](https://github.com/openfoam-ICL-UC/openfoam_intro_ES/wiki)

## Autores:
Catalina Pino Muñoz, Research Associate, Earth Science and Engineering Department, Imperial College London

Felipe Huerta, Profesor, Departamento de Ingeniería Química y Bioprocesos, Pontificia Universidad Católica de Chile
