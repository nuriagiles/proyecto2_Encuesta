Este es el proyecto 2, una encuesta realizada con IA que contiene un formulario, un filtro, cuatro gráficas y una seccion de comentarios.

Como abrirlo: 
Clic derecho sobre encuesta.html y cliqueas sobre "open with live server".

Saludos.

# Desplegament i flux de treball

El projecte s’ha desenvolupat utilitzant dues branques principals: **main** i **dev**. La branca **dev** s’ha fet servir per implementar i provar les noves funcionalitats abans d’integrar-les a producció. Un cop verificats els canvis, s’ha creat una **Pull Request (PR)** des de **dev** cap a **main**. Després de revisar els canvis, la PR s’ha fusionat correctament amb la branca principal.

L’aplicació està desplegada a Vercel i es pot consultar a la següent URL:

**https://proyecto2-encuesta.vercel.app**

Actualment les dades de l’enquesta es gestionen de manera local al navegador. La integració amb **Supabase** es realitzarà a la següent fase del projecte (IA5).

S’ha comprovat que no hi ha claus API ni informació sensible al repositori. A més, el fitxer **.gitignore** inclou **.env** per evitar la publicació accidental de variables d’entorn.
