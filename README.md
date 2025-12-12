# bigul
the bidirectional generic update language

```sh
stack new p1
```
- vscode 사용 시 `p1/`을 Open Folder 해야 haskell extension 제대로 작동함

## 실패
- 뭔 짓을 해도 안됨

```sh
ghcup set stack 2.15.3
ghcup install ghc 8.0.2
```
```
[ Error ] [GHCup-00841] Process "gmake" with arguments ["DESTDIR=/home/ser/.ghcup/tmp/ghcup-a05befea26a83972",
[ ...   ]                                 "STRIP_CMD=true", "install"] failed with exit code 2.
```
