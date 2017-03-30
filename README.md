# プログラムについて
 画像をアスペクト比を変えずにリサイズします．  
 余白は白で塗りつぶされます．JPEG画像に変換されます  

# 環境
 Python, OpenCVが必要  

# 使い方
 resize.pyがあるディレクトリにdata, resultというフォルダを作っておきます．  
 dataフォルダにリサイズしたい画像を入れます．  

 **[注意]** 実行時に初期化され，resultフォルダの中身は全消去されます．

 使用例  
 `python resize.py 200 280`  
 dataフォルダの画像がすべて縦200, 横280の画像にリサイズされます．  
