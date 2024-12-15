シェルのパイプ処理をc言語で再現した。

例えば、
< infile ls -l | wc -l > outfile
というシェルコマンドと同様の挙動を、
./pipex infile "ls -l" "wc -l" outfile
で再現。
