# DESIGN_LOG_2 – Justificación de Diseño (Ley de Fitts)

## Contexto
En la interfaz de navegación *Rumbo – Navegación Activa*, se realizó una modificación específica en los controles de interacción principales (botones de Zoom del mapa y botones de acción) con el objetivo de mejorar la usabilidad y accesibilidad, basándose en la **Ley de Fitts**.

## Ley de Fitts
La Ley de Fitts establece que el tiempo necesario para alcanzar un objetivo depende principalmente de dos factores:
- La **distancia** entre el usuario y el objetivo.
- El **tamaño** del objetivo interactivo.

En interfaces digitales, esto implica que **botones más grandes y cercanos** reducen el esfuerzo físico y cognitivo del usuario, especialmente en contextos táctiles o de uso rápido.

## Aplicación en los botones de Zoom
Los botones de Zoom del mapa (Leaflet) fueron modificados con las siguientes decisiones de diseño:

- Se **incrementó el tamaño del área clicable** a `50x50 px`, cumpliendo con estándares de accesibilidad táctil.
- Se aumentó el grosor del borde y el contraste visual para facilitar su identificación inmediata.
- Se añadió mayor separación entre los botones de Zoom (+ y -) para evitar errores de pulsación.
- Se posicionaron en la **esquina inferior derecha**, una zona de fácil alcance para el pulgar en dispositivos móviles.

Estas decisiones reducen el tiempo de adquisición del objetivo y minimizan errores de interacción, cumpliendo directamente con la Ley de Fitts.

## Aplicación en los botones de acción principales
Los botones de acción principales (“GRABAR RUTA” y “NUEVO PUNTO”) también fueron rediseñados:

- Se aumentó significativamente su tamaño (padding amplio y tipografía más grande).
- Se utilizaron formas redondeadas para ampliar visualmente el área interactiva.
- Se aplicó alto contraste de color y sombras para reforzar su jerarquía visual.
- Se colocaron centrados en la parte inferior de la pantalla, una zona natural de interacción en modo app.

Estas acciones convierten los botones en **targets grandes, claros y cercanos**, reduciendo el esfuerzo del usuario y mejorando la eficiencia de interacción.

## Conclusión
El aumento deliberado del tamaño y la accesibilidad de los botones de Zoom y de acción responde directamente a los principios de la Ley de Fitts, logrando una interfaz más rápida, intuitiva y segura, especialmente en escenarios de navegación activa y uso móvil.

### Prompt utilizado

"Crea una Landing Page HTML para una app de mapas llamada [RUMBO]. Debe tener un 'Hero' con una imagen de fondo de un mapa estilizado o topográfico, un título grande, y un botón CTA prominente que diga 'Explorar Mapa'. Usa Tailwind CSS. El diseño debe inspirar aventura/seguridad."