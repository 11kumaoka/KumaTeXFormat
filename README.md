# KumaTeXFormat

フォルダわけやbibTex, newcommand等を作ってあり，
includeも熊岡がよく使うものを事前に入れてあります．
適当に使ってみてください

Abstractフォルダはフォルダわけ等をしていないシンプルなもので，
Paperフォルダは筑波大の修論の仕様にしてありますが，
大したことはしていないので， 編集は楽だと思います．
Titleページも\maketilteではなく、適当なスペースを自身で設定しているため，
各自の用途に合わせて設定しやすいかと思います．

bibTexを有効にするためには以下のコマンドを自身のterminalのフォルダ内で実行してください．
エディタによってはbibTeXの設定もコンパイル時に勝手にやってくれる場合もあるかと思います．<br>
<br>
platex main <br>
pbibtex main <br>
platex main <br>
platex main <br>
dvipdfmx main <br>
