## pip upgrade를 했을 때, 설치에 실패하며 ModuleNotFoundError: No module named 'pip' 오류가 날 때
`pip`를 재설치해주면 된다. `PyPA`를 이용하면 쉽다.

`PyPA`라고 `Python Packaging Authority` 사이트가 있다. 파이썬 패키징에 사용되는 핵심 프로젝트 묶음을 유지, 관리하는 워킹 그룹이다.

아래와 같이 `curl`을 이용해 다운받고,

`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

아래 명령을 실행해 설치 할 수 있다.

`python get-pip.py`

출처 : https://devlog.jwgo.kr/2020/02/29/broken-pip-error/
