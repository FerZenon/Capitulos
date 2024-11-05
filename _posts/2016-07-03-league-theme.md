---
title: "CAPITULO 7"
layout: post
permalink: /league/
theme: league

slides:
 - title: "Medios de Transmisión"

 - title: "Concepto"
   slide-data: "Un medio de transmisión puede definirse en términos generales como cualquier cosa que pueda transportar información desde una fuente a un destino."

 - title: "Medios Guiados"
   slide-data: "Los medios guiados, son aquellos que proporcionan un conducto de un dispositivo a otro estos incluyen: Cable de par trenzado, cables coaxiales y fribra óptica."

 - title: "Cable de Par Trenzado"
   slide-data: "Un par trenzado consta de dos conductores (normalmente de cobre), cada uno con su propio aislamiento plástico, trenzados entre sí."

 - title: "Cable de Par trenzado"
   slide-data: "Los cables coaxiales se clasifican según sus clasificaciones de gobierno de radio (RG). Cada número RG denota un conjunto único de especificaciones físicas."

 - title: "Cable de fibra óptica"
   slide-data: " Un cable de fibra óptica está hecho de vidrio o plástico y transmite señales en forma de luz."

 - title: "Modos de propagración"
   slide-data: "La tecnología actual admite dos modos (multimodo y monomodo) para propagar la luz a lo largo de canales ópticos, cada uno de los cuales requiere fibra con diferentes características físicas.."

 - title: "Multimodo"
   slide-data: " El modo múltiple se puede implementar en dos formas: índice escalonado o índice graduado."

 - title: "Monomodo"
   slide-data: " El modo único utiliza fibra de índice escalonado y una fuente de luz altamente enfocada que limita los haces a un pequeño rango de ángulos."
   
 - title: "Conectores para cables de fibra óptica"
   slide-data: "Existen tres tipos de conectores para cables de fibra óptica:Conector ST, Conector SC y Conector Mt-RJ."

 - title: "Modos de Propagación de Fibra"
   slide-data: "Existen dos modos principales para propagar la luz en fibras ópticas: multimodo y monomodo, cada uno adecuado para diferentes aplicaciones y distancias."

 - title: "Tipos de Fibras Ópticas"
   slide-data: "Las fibras ópticas se definen por la relación entre el diámetro de su núcleo y el revestimiento, ambos expresados en micrómetros."

 - title: "Ventajas y Desventajas de Fibra Óptica"
   slide-data: "La fibra óptica ofrece mayor ancho de banda, inmunidad a interferencias y seguridad, pero requiere instalación especializada y es más costosa que otros medios."

 - title: "Cable Coaxial"
   slide-data: "El cable coaxial transporta señales de alta frecuencia y tiene un conductor central de cobre, rodeado de una funda aislante y un conductor exterior metálico que protege contra el ruido y completa el circuito."

 - title: "Normas de Cable Coaxial"
   slide-data: "Los cables coaxiales se clasifican según el número RG, que define especificaciones como el calibre del conductor, tipo de aislante, blindaje y cubierta."

 - title: "Conectores de Cable Coaxial"
   slide-data: "Entre los conectores coaxiales se encuentran el BNC, para conectar el cable a un dispositivo, el conector BNC T para derivaciones y el terminador BNC para evitar reflexiones de señal."
   
 - title: "Modos de Propagación de Fibra"
   slide-data: "Existen dos modos principales para propagar la luz en fibras ópticas: multimodo y monomodo, cada uno adecuado para diferentes aplicaciones y distancias."

 - title: "Tipos de Fibras Ópticas"
   slide-data: "Las fibras ópticas se definen por la relación entre el diámetro de su núcleo y el revestimiento, ambos expresados en micrómetros."

 - title: "Ventajas y Desventajas de Fibra Óptica"
   slide-data: "La fibra óptica ofrece mayor ancho de banda, inmunidad a interferencias y seguridad, pero requiere instalación especializada y es más costosa que otros medios."

 - title: "Medios No Guiados (Inalámbricos)"
   slide-data: "Los medios no guiados transportan ondas electromagnéticas sin conductor físico, utilizando el espacio libre para transmisión. Es el caso de la comunicación inalámbrica."

 - title: "Métodos de Propagación Inalámbrica"
   slide-data: "Los métodos de propagación incluyen: terrestre (ondas de baja frecuencia), en el cielo (frecuencia media) y en línea de visión (alta frecuencia)."

 - title: "Antena Omnidireccional"
   slide-data: "Las antenas omnidireccionales envían señales en todas direcciones, siendo común en radiofrecuencia, aunque son susceptibles a interferencias."

 - title: "Ondas de Radio"
   slide-data: "Las ondas de radio son omnidireccionales y no requieren alineación entre antenas, lo cual facilita su recepción, aunque pueden sufrir interferencias."

 - title: "Microondas"
   slide-data: "Las microondas son unidireccionales y requieren que las antenas estén alineadas. Se utilizan en aplicaciones de comunicación a largas distancias."

---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
{% endfor %}
