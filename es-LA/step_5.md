## Mejora el modelo

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/66bpBQrxSp4?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

Los datos de entrenamiento están sesgados, ya que solo incluyen manzanas verdes.

Para reducir el sesgo, ncesitas agregar ejemplos adicionales de manzanas a la clase 'Manzana'.

\--- task ---

Descarga una [carpeta con más imágenes de manzanas](https://drive.google.com/drive/folders/1OIuoG7go72c7QririIpykJ4tW-arrtfA){:target="_blank"}.

\--- /task ---

\--- task ---

Descomprime la nueva carpeta.

\--- /task ---

\--- task ---

En la clase 'Manzana', agrega algunas imágenes de muestra de una de las carpetas que acabas de descargar.

Elige las imágenes que se más se parezcan a tu manzana **roja**.

**Consejo:** También puedes usar tu cámara web para tomar imágenes de tu manzana roja.

**Consejo:** Solo necesitas agregar unas pocas imágenes adicionales a tu clase 'Manzana'.

\--- /task ---

### Veulve a entrenar el modelo

\--- task ---

Haz clic en **Entrenar Modelo**.

![El botón 'Entrenar modelo'.](images/train_model.png)

\--- /task ---

Cuando el modelo esté entrenado, se abrirá el panel de Vista previa.

\--- task ---

Sostén tu manzana **roja** frente a la cámara web para probar el modelo nuevamente.

El modelo debería realizar una predicción con una **puntuación de fiabilidad más alta** de que es una **manzana**.

\--- /task ---

\--- task ---

Sostén tu tomate en frente de la cámara web.

El modelo podría realizar una predicción con una **puntuación de fiabilidad más baja** de que es un **tomate**.

Esto se debe a que has agregado datos de entrenamiento a la clase 'Manzana' con imágenes que se parecen más a los tomates.

\--- /task ---

## --- collapse ---

## title: Nota para los educadores

Puedes optar por introducir a los estudiantes el concepto del sesgo ético que puede resultar del uso de datos de entrenamiento sesgados.

\--- /collapse ---
