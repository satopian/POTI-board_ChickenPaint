# POTI-board ChickenPaint 対応版

## 概要
![image](https://user-images.githubusercontent.com/44894014/117165096-293c9000-ae00-11eb-91f7-88a4fb26eb8c.png)  
- [thenickdude/chickenpaint: An HTML5 Port of the ChibiPaint multi-layer Oekaki painting tool](https://github.com/thenickdude/chickenpaint)  
- 従来のPaintBBS NEO、しぃペインターに加え、ChickenPaintも使えるようにしたPOTI-boardです。  

DEMO [お絵かき掲示板](https://pbbs.sakura.ne.jp/cgi/neosample/chibi/index.html)

### [2021/05/09] 
- iPadでもChickenPaintを使えるようにしました。  
- 具体的には、マルチタッチでデバイスの幅が767px以下の環境でmobile判定。
- mobile判定されなかった時は、しぃペインターやChickenPaintの選択メニューが出ます。
- iPadでもしぃペインターの選択画面がでますが現時点では使えるのか使えないのかわかりません。
- 著作表示にChickenPaintを追加しました。
### [2021/05/06] 
- レスお絵かきのアプリの切替えに対応。
- JavaScriptによるモバイル判定をHTMLに追加。
- モバイルと判定された時はNEOしか起動しないようにした。
- ChickenPaintのリソースディレクトリの位置関係を整理。

### [2021/05/05] 
- PaintBBS NEO、しぃペインター、ChickenPaintを選択式にして、それぞれのお絵描きアプリを起動可能にした。
- 続きを描くときに
- PaintBBS NEO、しぃペインターで動画があるときは、同じアプリが起動。
- ChickenPaintのレイヤーフィアルがあるときは、ChickenPaintが起動します。

### [2021/05/05] 
- 対応開始



