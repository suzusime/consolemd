本家: [kneufefld/consolemd](https://github.com/kneufeld/consolemd)

msys2のためにUTF-8で強制表示しようとしたけど駄目だった。

でもpython3.6で動くようにはなっている。

## インストール
```bash
pip install https://github.com/suzusime/consolemd/raw/master/dist/consolemd-0.3.2-py2.py3-none-any.whl
```

## ビルド
```bash
pip2 install wheel
python2 setup.py bdist_wheel --universal #python2, python3両方対応のもの（py2.py3）はpython2でビルド
pip install dist/consolemd-0.3.2-py2.py3-none-any.whl #pip3でインストール
```

