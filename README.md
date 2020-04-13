[[F12]は使わせて!!](https://github.com/furyutei/LetMeUseF12)
==============================================================================

- License: The MIT license  
- Copyright (c) 2020 風柳(furyu)  
- 対象ブラウザ： Google Chrome、Firefox

サイトによっては制限されている、[F12]ほか幾つかのキー操作を可能に。  


■ インストール方法 
---
### ユーザースクリプト
Google Chrome＋[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) や Firefox＋[Tampermonkey](https://addons.mozilla.org/ja/firefox/addon/tampermonkey/) 等のユーザースクリプトが動作可能な環境で、  

> [[F12]は使わせて!!](http://furyutei.github.io/LetMeUseF12/src/js/LetMeUseF12.user.js)  
                                
をクリックし、指示に従ってインストール。  


■ 動作について
---
keydown/keyupイベントを監視し、幾つかのキー操作についてはデフォルト動作を優先させる。  
