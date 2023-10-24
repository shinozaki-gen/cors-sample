# cors-sample

docker-compose up -d 
で起動します

Port番号の 8100と8101をあけておいてください

# 構成
[front/index.html](front/index.html)

http://localhost:8100

で表示されるHTMLになります。

[api/](api/)

success.php

fail.php

どのような処理をしてCORS対応をしているか確認してみてください

# 動作確認
http://localhost:8100
<img width="539" alt="スクリーンショット 2023-10-24 18 35 36" src="https://github.com/shinozaki-gen/cors-sample/assets/102288364/d079fdc6-1407-4a3e-ad32-137c9adade1e">

↑
のような画面が表示されます
successボタンを押すとCORSエラーにならないで
failボタンを押すとCORSエラーになります。
DevToolでどのようなHeader情報になっているか確認してみてください。
