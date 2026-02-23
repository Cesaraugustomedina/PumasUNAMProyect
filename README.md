# PumasUNAMProyect
Este es un repositorio donde desarrollaré funciones de Inteligencia Deportiva del club Pumas UNAM para analizar a profundizar fortalezas y debilidades


1. Análisis de la Plantilla (Squad Management)

- Pirámide de edad:  Clasificar a los jugadores en: Prospectos (Cantera), Pico de Rendimiento (24-29 años) y Veteranos.
  Pumas históricamente necesitan equilibrio para mantener la intensidad en C.U.

- Análisis de Profundidad: Mapear dos jugadores por posición y evaluar la brecha de calidad.
  Si el titular se lesiona, ¿cuánto disminuye el rendimiento esperado?

-Disponibilidad Física: Usar datos históricos para identificar jugadores propensos a lesiones,
 Un factor clave dado el desgaste por el horario de juego local (domingos a mediodía)

2. Estilo de Juego (Tactical Analysis)

Pumas se identifican con la presión alta y las transiciones rápidas. Debes medir si esto se está cumpliendo usando métricas avanzadas:

- PPDA (Passes per Defensive Action): Mide la intensidad de la presión. Un PPDA bajo indica que Pumas no deja salir al rival, ideal para asfixiar en la altura de CDMX.

- Mapas de Calor y Redes de Pases: Identifica si el equipo depende demasiado de un solo jugador (ej. el "Chino" Huerta en temporadas pasadas) para progresar.

- Verticalidad: Mide cuántos metros progresa el balón hacia adelante por cada pase. Los Pumas suelen ser más efectivos cuando es directo que cuando tienen posesiones largas.


3. Identificación de Áreas de Mejora

Se utilizará el concepto de KPIs (indicadores clave de desempeño):

- Eficiencia en Centros: Pumas suelen llegar mucho por banda; analiza el porcentaje de remates tras centro. Si es bajo, la mejora está en la ocupación del área o en la calidad del lanzador.

- Defensa de Transiciones: ¿Cuántos goles recibe el equipo cuando pierde el balón en ataque? Esto indicaría una mala vigilancia defensiva.
  
-Efectividad en Balón Parado: En el fútbol moderno, el 30% de los goles vienen de aquí. Evalúa si el equipo está aprovechando su altura y potencia física.


Herramientas Sugeridas para el Proyecto

Para que el análisis tenga nivel profesional, utilizaremos este "stack" tecnológico:

Datos: Intenta conseguir datasets en plataformas como Wyscout o Opta (o usa web scraping en sitios como FBref).

Lenguajes: Usa Python con las librerías mplsoccer para dibujar canchas y pandas para el procesamiento.

Visualización: Crea un dashboard en Tableau o Power BI donde el Director Técnico pueda ver el rendimiento individual comparado con el promedio de la Liga MX.

El "Plus" de Inteligencia Deportiva: 

Scouting: Un jugador clave va a ser vendido. Nuestro trabajo es presentar una lista de 3 candidatos (usando Similarity Scores) que tengan métricas similares, que entren en el presupuesto del club y que cumplan con el perfil de "garra" universitaria.


