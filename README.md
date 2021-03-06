# House-Pointer
 
"House-Pointer"はjavascriptを用いた木造建築の劣化情報を知ることができるwebアプリです。
 
 
### 使用例
<img src="https://i.imgur.com/QtVohNl.png" width="480">
この画像は実際に木造建築の画像を読み込ませた際の処理結果です。  赤い枠に囲まれている部分が劣化していると判断された部分です。


### ファイル構成
 ファイル構成は以下の通りです。  
・index.html  
・404.index    
・css  
　|-style.css  
・diagnosis-heatmap  
　|-cascade.xml  
　|-index.html  
・distortion-diagnosis  
　|-index.html  
・img  
　|-disaster.svg  
　|-eye.svg  
　|-foto.svg  
　|-lightbulb.svg  
　|-logo.svg  
　|-logo-icon.jpg  
　|-logo-icon.png  
　|-logo-icon.svg  
　|-loupe.svg  
　|-rain.svg  
　|-snow.svg  
・past-disaster-info  
　|-index.html

### 使い方

ローカルでは使用できない関数などを含むので、firebaseなどサーバー上にアップロードして使用してください。  

### 注意点
・劣化情報診断において、一度画像を読み込んだ後にもう一度画像を読み込ませても動作しません。 
　一度ページを更新してから画像をアップしてください。  
・使用する端末により処理速度や処理結果に違いがあります。

 
### 作成者
作成者:山田耕太郎、宮川夢空、清水陸、岡田達也、笠島海音  
指導教員:村田知也  
所属:独立行政法人国立高等専門学校機構福井工業高等専門学校

