# Template_of_CSmap_distributor
CS 立体図をタイル地図として配信するためのテンプレートです
Template repository to distibute CS topographic map as map tiles

# DEMO
このレポジトリをクローンして、tileのフォルダーに地図タイルを置いてください。地図タイルに関する情報をinfmap.jsonに記載してください。
sample/sample02.html では地図タイルに関する情報をスクリプト内に記載して、パラメータが自動的に設定されるようになっています。
sampleフォルダーのtile/myregion には東広島地域のZoom Level 6-14 のCS立体図を格納してあります。
sample/test_url_params.html では、URLパラメーターで場所とzoom levelを指定してマーカを表示できるようになっています。
例えば、緯度：34.3099、経度：132.753261、zoom level: 14 の場合は、下記のようにURLのhtmlの後ろに ? をつけて、その後ろにパラメータを指定してください。

test_url_params.html?y=34.3099&x=132.753261&z=14

特定の場所について議論する際に、このパラメータ付きのURLを、slackなどに張り付けてリンクをだどることで、効率的な情報交換が出来ると思います。とくに、災害時などには便利ではないかと思います。

