[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Diego222104/MSF-Practica-2)

## Autor
Torres Velez Diego Raul

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l22210429@tectijuana.edu.mx

## Objetivos general
Diseñar un controlador que permita formular un protocolo de tratamiento para que un paciente con enfisema (caso) presente la misma presion alveorlar que un individuo sano (control).

## Actividades
1. Calcular analíticamente la función de transferencia del sistema pulmonar.
2. Establecer el modelo de ecuaciones integro-diferenciales.
3. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.
4. Diseñar el controlador con Simulink utilizando el bloque PID Controller y la herramienta Tune para sintonizar los valores óptimos para cada una de las ganancias kP, kI y kD.
5. Ilustrar el cambio del flujo de aire y el volumen tidal en respuesta a las siguientes formas de onda de presion sinusoidal en la apertura de la via aerea [Pao(t)]:
  a) 15 respiraciones por minuto con una amplitud (A) de 2.5 cmH2O, es decir respiracion           normal.
   b) 30 respiraciones por minuto con una amplitud (A) de 1.5 cmH2O, es decir respiracion           elevada o taquipnea.
6. Determinar la respuesta a la funcion sinusoidal [u(t)= Asin ω=t] en el intervalo t∈[0,30] (segundos), en Python, Simulink y Multisim en lazo abierto y en lazo cerrado con el controlador.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018.
