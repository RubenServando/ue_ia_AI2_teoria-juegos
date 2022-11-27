# ue_ia_AI2_teoria-juegos
Actividad de Inteligencia Artificial que resuelve una teoría de juegos (3 en raya).
Con esta actividad calculamos la velocidad de cómputo utilizando algoritmos de teoría de juegos (3 en raya), el código está implementado en GoogleColab . 
A partir de un código aportado, se trata de optimizar el cómputo realizando la poda de ramas innecesarias en un árbol de desición. 
El tiempo de procesamiento de la búsqueda de la IA implementada se reduce considerablemente en comparación con el original, tal como vemos a continuación:

Cómputo SIN poda                        -->     Cómputo CON poda:
Cómputo 1 --> Evaluacion: 5.1661334s    -->     Evaluacion: 1.9440966s
Cómputo 2 --> Evaluacion: 0.057585s     -->     Evaluacion: 0.0265758s
Cómputo 3 --> Evaluacion: 0.0011439s    -->     Evaluacion: 0.0008054s
Cómputo 4 --> Evaluacion: 0.0001688s    -->     Evaluacion: 6.15e-05s    
Cómputo 5 --> Evaluacion: 2.69e-05s     -->     Evaluacion: 1.76e-05s 
