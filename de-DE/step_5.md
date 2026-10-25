## Verbessere das Modell

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/66bpBQrxSp4?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

Die Trainingsdaten sind einseitig, weil sie nur grüne Äpfel enthalten.

Um die Einseitigkeit zu reduzieren, musst du der Klasse „Apple“ zusätzliche Beispiele von Äpfeln hinzufügen.

Lade einen [Ordner mit weiteren Bildern von Äpfeln](https://drive.google.com/drive/folders/1OIuoG7go72c7QririIpykJ4tW-arrtfA){:target="_blank"} herunter.

Entpacke den neuen Ordner.

Füge der Klasse „Apple“ einige Beispielbilder aus einem der Ordner hinzu, die du gerade heruntergeladen hast.

Wähle Bilder aus, die deinem **roten** Apfel am ähnlichsten sehen.

**Tipp:** Du kannst auch mit deiner Webcam Bilder von deinem roten Apfel machen.

**Tipp:** Du musst nur ein paar zusätzliche Beispiele zu deiner 'Apfel'-Klasse hinzufügen.

### Trainiere das Modell erneut

Klicke auf **Modell trainieren**.

![Die Schaltfläche „Modell trainieren“.](images/train_model.png)

Wenn das Modell trainiert ist, wird das Vorschaufenster geöffnet.

Halte deinen **roten** Apfel vor deine Webcam, um das Modell erneut zu testen.

Das Modell sollte die Vorhersage mit einer **höheren Sicherheit** treffen, dass es sich um einen **Apfel** handelt.

Halte deine Tomate vor deine Webcam.

Das Modell könnte die Vorhersage mit einer **niedrigeren Sicherheit** treffen, dass es sich um eine **Tomate** handelt.

Dies liegt daran, dass Du der Bildklasse „Apple“ Trainingsdaten hinzugefügt hast, die eher wie Tomaten aussehen.

---

## title: Hinweis für Lehrer

Sie könnten den Lernenden das Konzept der ethischen Voreingenommenheit näherbringen, die sich aus der Verwendung verzerrter Trainingsdaten ergeben kann.

