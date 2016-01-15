# terminal에서 subl 명령어로 Sublime-Text 실행하기

```sh
# [sudo] OSX 관리자 권한으로 프로그램을 실행합니다.
# [ln]   link를 생성할 때 쓰는 명령어입니다.
# [-s]   심볼링크를 생성하는 옵션입니다.
# Sublime Text Application 설치 경로에서 `subl` 명령어를 찾아 실행 가능하도록 설정합니다.
$ sudo ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl
```