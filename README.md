# 迷路ゲーム

【制作者】神尾 巧(法政大学)  
【使用言語】Python(pygame)  
【概要】2Dと3D表示の迷路を進んでいくゲーム  

【操作方法】  
Escapeキー：ゲームを終了  
タイトル画面  
左右矢印キー：選択  
エンターキー：決定  
ゲーム画面  
左右矢印キー：向き変え  
上下矢印キー：前進/交代  
スペースキー：ゴールまでのルートを表示/非表示  
エンターキー：(ゴールにいるとき)次の階へ  

【仕様】  
迷路は起動時、階を進むごとに穴掘り法で生成される  
タイトル画面では迷路の大きさをsmall：11×11、medium：21×21、big：31×31から選ぶ  
画面左に2D(上からの視点)、画面右に3D(一人称視点)の視点が表示される  
正しいルートは2D視点ではピンク色のタイルで表示されて3D視点では赤い矢印で表示される  
