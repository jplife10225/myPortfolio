# Wu Sungyi's Portfolio
wu sungyiです。<br>
よろしくお願いいたします。<br>

# 一ヶ月間ゼロからdjango appをherokuにデプロイしてみた
<strong>url</strong> : https://wusungyi-portfolio.herokuapp.com/<br>
<strong>環境</strong>：<br>
<strong>OS</strong>：Windows 10(20H2) with Ubuntu 20.04.2 LTS (WSL)<br>
<strong>デザイン/テンプレート</strong> :<br>
Adobe XD /Personal Portfolio Template in Adobe XD(https://xdfile.com/personal-portfolio-template-in-adobe-xd/)<br>
<strong>言語</strong> : <br>html, css (sass), Python(Django)<br><br>
<strong>動機</strong>：<br>大学時代にPythonやりましたので、djangoで自分のポートフォリオを作ってみたいと思い、stackflow,qiitaで調べながら作りました。<br>
<strong>実装方法</strong>:<br>html,cssはある程度理解しているから、今回はAdobe XDとsassを用いて作りました。大体の流れはこんな感じです：<br>
1.Adobe XDのテンプレートで自分のアイディアを加え、それを画像に書き込みます。<br>
2.ローカルでVS CodeでLinux(WSL)環境を構築し、Adobe XDのデザイン通りhtmlに移します。<br>
3.ローカルで仮想環境を構築し、django appのテンプレートを作ります。<br>
4.画像データをdjangoのstaticフォルダに移し、サーバーに認識させます。<br>
5.herokuのアカウントとデプロイするためのファイル(Procfileなど)を作り,ローカルの仮想環境でgitでinit,commitします。<br>
6.herokuのサーバーにデプロイします。<br>
<strong>今後やるべきこと</strong>:<br>
1.AIモデルのデプロイ。元々は実装する予定ですが、忙しくて諦めました。今度は実装したいです。<br>
2.javascript及びjqueryの勉強。sassだけは物足りなさがあるので今度は完璧にしたいです。<br>

# Pytorchでスリーサイズを予測するという試み
url : https://colab.research.google.com/drive/1kSgDFKG1lSkf-cTFytL1_6v23H3Ci3Vc?usp=sharing<br>

参考資料 : https://qiita.com/nardtree/items/a2a5ec50e3b17c662864

<strong>動機</strong>：<br>スリーサイズがわかればAIを通じて現場で試着しなくても服のサイズ知れるからです。<br>私にとって服選びはめんどくさいので、<br>ディープラーニングを通じて同じ悩みを抱えてる人々に応援したいです。<br>
<strong>実装方法</strong>:<br>ネット上で違う人がtensorflow,kerasを用いてやったことがあるらしいので、その人がスクレイピングしたデータをダウンロードしました。<br>
ResNet,EfficientNetなどの訓練済みCNNネットワークに転移学習させ、約20%の正解率を出せました。<br>
<strong>今後やるべきこと</strong>:<br>
1.データの調整。スリーサイズをちゃんと認識してるか否かはブラックボックス化してるところがありますので、今後より質がいいデータを入手したいです。<br>
2.CNNよりGANのほうがいいかもしれないので勉強中です。<br>
# Pytorch　LSTMモデルで株価を色々挑戦してみた
url : https://colab.research.google.com/drive/1LNK9CDDc-bcJ_JaVtyxSFJWr7Wt7DSdZ?usp=sharing<br>
参考資料は準備中です。。

