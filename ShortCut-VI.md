# ShortCut: vi

* 이동: 
1. 첫행으로: 
<kbd>gg</kbd>

2. 마지막으로: 
<kbd>shfit+g</kbd>

3. 10행으로: 
<kbd>:10</kbd>

4. 행의 처음으로:
<kbd>^</kbd>

5. 행의 끝으로 :
<kbd>$</kbd>

<kbd>:set nu</kbd> :라인번호
<kbd>:set nonu</kbd> "라인번호 감추기
<kbd>:set paste</kbd> 한 후 붙여넣기: 인덴트가 살아있다.

<kbd>:%s/선택단어/바꿀내용/g</kbd> (대소문자구분)
<kbd>:%s/선택단어/바꿀내용/ig</kbd> (대소문자무시)

<kbd>i</kbd>: 바로 앞에 입력모드
<kbd>a</kbd>: 바로 뒤에 입력모드
<kbd>u</kbd>: Undo : Ctrl+r
<kbd>x</kbd>: delete
<kbd>r</kbd>: change 1 char
<kbd>A</kbd>: insert mode at line end
<kbd>o</kbd>: 다음줄에 입력모드 시작
<kbd>O</kbd>: 윗줄에 입력모드 시작
<kbd>dd</kbd>: 한줄 지우기
<kbd>yy</kbd>: 한줄 복사
<kbd>p</kbd>: 붙여넣기
<kbd>v</kbd>: visual mode 전환
<kbd>Ctrl + f</kbd> : page down
<kbd>Ctrl + b</kbd> : page up
<kbd>g</kbd>: go to first page line
<kbd>G</kbd>: go to last page line
<kbd>Shift+$</kbd>: go to last at line (End key)
<kbd>Shift+^</kbd>: go to first at line (Home key)
<kbd>Shift+arrow (상하)</kbd>: 페이지 이동
<kbd>Shift+d</kbd> : 현재 라인에서 커서 뒷 부분 다 삭제
<kbd>:!</kbd> : 밖으로 잠깐 나간다.(커맨드 라인으로 나간다)
<kbd>:!명령어</kbd>: 밖에서 명령어 실행 (ex: :!python a.py)


--------------------------------------------------------------------------------
* 찾기: (그 다음 문자열를 탐색(계속 탐색)을 하려면 소문자 "n" 을 누르면 되고    
* 이전 문자열를 탐색(계속 탐색 - 역방향)을 하려면 대문자 "N") 
--------------------------------------------------------------------------------
1. 현재 커서 위치에서 아래방향으로:
<kbd>:/text</kbd>

2. 현재 커서 위치에서 윗방향으로:
<kbd>:?text</kbd>

3. apple로 시작하는 문자열 찾기:
<kbd>/^apple</kbd>

--------------------------------------------------------------------------------
* copy & paste: (esc key를 눌러서 편집모드에서 빠져나와 v key를 눌러서 visual mode로 진입한다. 
* <kbd>Ctrl+v key</kbd>를 누르면, 사각형 형태로 블록이 선택됨) 
--------------------------------------------------------------------------------
1. visual mode에서 화살키로 선택블록을 만든다.
2. <kbd>y</kbd> key를 누른다 (copy)
3. <kbd>p</kbd> key를 누른다(paste)


--------------------------------------------------------------------------------
* 화면분할
--------------------------------------------------------------------------------
<kbd>:sp</kbd> 또는 <kbd>:split</kbd>을 입력하거나 <kbd>Ctrl + w + n</kbd>을 누르면 수평으로 분할 창이 1개씩 생깁니다.

<kbd>:vs(vsplit)</kbd>을 입력하거나 <kbd>Ctrl + w + v</kbd>를 누르면 수직으로 분할 창이 1개씩 생깁니다.
만약 분할 창을 닫기 위해서는

<kbd>:close</kbd>를 입력하거나 <kbd>Ctrl + w + c</kbd>를 누르면 됩니다.

여러 개의 분할 창을 이동하려면

<kbd>Ctrl + w + w</kbd>를 누르면 됩니다.

아래의 분할 창으로 이동하려면 <kbd>Ctrl + w + j</kbd>를 누르면 되고,

위의 분할 창으로 이동하려면 <kbd>Ctrl + w + k</kbd>를 누르면 됩니다.

<kbd>:resize</kbd> 명령과 숫자를 입력해서 창 크기를 조정할 수 있습니다.

<kbd>Ctrl, w, +</kbd> 또는 <kbd>Ctrl, w, -</kbd> 또는 <kbd>Ctrl, w, =</kbd>를 눌러서도 창 크기를 조정할 수 있습니다.