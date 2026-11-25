# Simulador de pacientes virtuales

**Abrir el simulador:** https://milupdf-hub.github.io/simulador-pacientes-virtuales/

Simulador del sistema cardiovascular que funciona entero en el navegador, sin instalar nada. Genera
pacientes virtuales sanos y con enfermedades cardiovasculares y muestra su circulación latido a
latido: tensión arterial, gasto cardíaco, presiones de llenado, curvas de presión y volumen y bucle
presión-volumen del ventrículo izquierdo.

## Qué se puede hacer

- **Paciente aleatorio:** elegir una enfermedad (insuficiencia cardíaca, hipertensión, estenosis
  valvulares, shocks, hemorragia…) y generar un paciente con un perfil realista de la población
  española (edad, sexo, altura, peso, tabaco y diabetes).
- **Crear paciente:** definir el perfil, la medicación y los parámetros del corazón y de los vasos, y
  simular una hemorragia con o sin barorreflejo.

## Modelo

- Modelo hemodinámico mínimo de Smith, Chase, Nokes, Shaw y Wake (2004), *Medical Engineering &
  Physics* 26:131–139.
- Barorreflejo carotídeo de Ursino (1998), *American Journal of Physiology* 275:H1733–H1747.
- Extensiones propias: sístole que se acorta con la frecuencia, presiones de llenado realistas,
  escalado al tamaño corporal y perfil del paciente, cada una con su fuente bibliográfica.

Integración con Runge-Kutta de 4.º orden (paso de 1 ms). Los resultados coinciden con los del modelo
en OpenCOR.

## Aviso

Herramienta docente y de investigación. Los pacientes son simulados (datos sintéticos) y el
simulador **no sirve para diagnosticar ni tratar a pacientes reales**.

## Autoría

Miloud Slimani (ILIS, Université de Lille), prácticas en el instituto DaSCI de la Universidad de
Granada, 2026. Tutora: Dra. Rocío Romero Zaliz.
