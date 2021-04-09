# cpp-opencv-cmake
practice setting the opencv enviornment using cmake

## 実行コマンド

```
mkdir build
cd build
cmake .. .
make
cd ..
./build/Main
```

画像が表示されればok.

ポイント
* 自分のソースコードとcmakeのbuildにより生成されるファイルを分離するために，buildディレクトリを作ってから"cmake .. ."によりCMakeLists.txtを実行．
* "make"によりコンパイルして./Mainを生成．
* 画像ファイルとソースコードと同じ階層で実行する必要があるので, "cd .."で上の階層に移ってから，"./build/Main"を実行．