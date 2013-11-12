eVocaloid用テキスト→SYS-EXコンバータ
=======

まだ作成中

ruby evocaloid.rb [テキストファイル] 

テキストはひらがなで書きます。

<dl>
<dt>あいうえお
<dt>かきくけこ
<dt>さしすせそ
<dt>ぴょぴょぴょにゅにゅにゅ
<dt>うぉうぉうぉ
<dt>きぇきぇきぇきぇきぇ
<dt>つぁつぁつぁつぁ
</dl>

こんな感じ。

出力は今のところ16進をテキストで吐き出してます。
あとで、midi周りの部分合わせて出力する予定。

いまはこんな感じ

<dl>
<dt> # 発音記号 a i M e o
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
<dt> # 発音記号 ka k'i kM ke ko
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
<dt> # 発音記号 sa Si sM se so
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
<dt> # 発音記号 p'o p'o p'o JM JM JM
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
<dt> # 発音記号 wo wo wo
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
<dt> # 発音記号 k'e k'e k'e k'e k'e
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
<dt> # 発音記号 tsa tsa tsa tsa
<dt> F0 43 79 09 00 50 11 
<dt> 00 F7 
</dl>

