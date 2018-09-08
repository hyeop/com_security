com_security
==================

정보보안, 화이트 해커에 관심이 생겨서 시작하려 했지만, 어떤 것 부터 시작해야 하는지 몰라서 무작정 서울로 올라갔다.<br>
지난 1년동안 서울에서 IT 학원을 다니면서 IT 관련 여러 분야를 접해보았다.<br>
학원에서는 정보보안을 크게 다음과 같이 분류하고 있었다. 

* 네트워크 보안
* 시스템 보안
* 웹 어플리케이션 보안

<br><br><br>

Net_Sec
----------------------
네트워크, 프로토콜에 대한 전반적인 지식이 필요하다.<br>
네트워크 보안은 Packet Tracer, GNS3 가상환경을 구축해서 Host간의 통신을 통해 학습한다.<br>
따라서, 네트워크 기초, CCNP Router, CCNP Switch 관련책을 통해 네트워크 통신 및 기술에 관한 내용을 공부한뒤,<br>
Packet Tracer 나 GNS3(추천)의 사용법을 익혀야한다. Host 간의 통신은 wireshark 라는 툴을 통해 확인한다.<br>
보안을 공부하게 되면 Kali Linux 를 사용하게 되는데, Linux 에 대한 기초적인 명령어를 알고 있다면 큰 도움이 됩니다.

* 준비물 : Packet Tracer (초반 학습에 효과적), GNS3, Virtual Machine, Kali Linux (wire shark 설치되어있음), ..
<br><br><br><br>

System_Sec
----------------------
운영체제에 대한 이해가 필요하다.<br>
운영체제에 따라 공격자가 접근하는 목적이 달라진다.<br>
공격자가 원하는 프로그램을 원하는 시스템에서 실행시키는게 주목적이 될 수 있고 (윈도우), <br>
관리자 권한을 획득하는 것이 목적이 될 수 있다 (리눅스). <br>
각 운영체제데 대한 지식과, 각 운영체제의 권한의 체계, Password 관리에 대한 이해가 필요하다. <br>
Password Cracking, Backdoor 를 이용한 시스템 침투, Buffer Overflow 를 통한 원하는 프로그램 실행(**리버싱**), <br>
이 외에도 FSB(Format String Bug), Race Condition 등.. 에대한 학습이 이루어진다. <br>

* 준비물 : 디버그 프로그램(OllyDbg), OS(Window, Linux)에 대한 이해, IDA .. 

<br><br><br><br>

Web_Sec
----------------------
우선적으로 웹에 대한 구조에 대한 이해가 필요하며, 웹 프로그래밍 언어와 데이터 베이스에 대한 학습이 필요하다. <br>
네트워크에 대한 어느정도의 이해가 학습에 도움을 줄 수 있다.<br>
Cookie 에 대한 개념과 Cache, Encoding 에 대한 이해,<br>
Request 와 Response 메세지를 보고 해석할 수 있는 능력이 요구된다. <br>
XSS(Cross Site Scription), SQL injection 등의 공격을 수행한다. <br>

* 준비물 : Web Message 분석 툴, DataBase 명령어, Script 언어 등..

<br><br><br><br>

----------------------
**정보보안은 폭이 매우 넓기 때문에, 모든과목을 배우는 것이 플러스가 될 수 있다.<br>
지극히 개인적인 견해지만, 그 중에서도 ★ 네트워크 ★와 ★ 프로그래밍 언어 ★에 대한 학습은 필수 적인 것 같다.**

----------------------












