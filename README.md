#LabTool-OneClick-Elf  
ラボツールのワンクリック起動バイナリを作る方法です。  
shcが必要です。以下からDLしてください。  
http://www.datsi.fi.upm.es/~frosal/
shcをビルド後コマンドラインで  
shc -v -r -T -f /PATH/oneclick.sh 
にてビルドするとバイナリが生成されます。そのバイナリを実行することでワンクリック起動を実現しています。  
確認した環境は  
Linux 3.13.0-31-generic #55-Ubuntu SMP Tue Jul 1 15:51:53 UTC 2014 x86_64 x86_64 x86_64 GNU/Linux  
になります。Ubuntu 14.04です。  
gksuでsudo実行してるのは、原因不明ですが描画がこちらのほうがキレイなのでそれだけの理由です。ご自由に。
