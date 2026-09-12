## モデルを改善する

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/66bpBQrxSp4?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

トレーニングデータには緑のリンゴのみが含まれているため、偏りがあります。

偏りを減らすには、「リンゴ」クラスにリンゴの例を追加する必要があります。

[リンゴの画像がもっと入ったフォルダ](https://drive.google.com/drive/folders/1OIuoG7go72c7QririIpykJ4tW-arrtfA){:target="_blank"}をダウンロードしてください。

新しいフォルダを解凍してください。

「リンゴ」クラスに、先ほどダウンロードしたフォルダのいずれかから画像サンプルをいくつか追加してください。

あなたの**赤い**リンゴに最も似ている画像を選んでください。

**ヒント:** ウェブカメラを使って赤いリンゴの写真を撮ることもできます。

**ヒント:** 「リンゴ」クラスにいくつかのサンプルを追加するだけで済みます。

### モデルを再度トレーニングする

**モデルをトレーニング**をクリックします。

![「モデルをトレーニング」ボタン](images/train_model.png)

モデルの学習が完了すると、プレビューパネルが開きます。

モデルを再度てすとするには、**赤い**リンゴをウェブカメラに向けてください。

モデルは**リンゴ**であることを**高い確信度**で予測するはずです。

トマトをウェブカメラに向けてください。

モデルは**トマト**であることを\*\*低い確信度\*で予測する可能性があります。

これは、トマトによく似た画像を含む「リンゴ」クラスのトレーニングデータを追加したためです。

---

## title: 教育関係者の皆様へ

偏ったトレーニングデータを使用することによって生じる倫理的バイアスの概念を学習者に紹介することもできます。

