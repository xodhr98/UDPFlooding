# UDP Flooding Malware 제작

### 전체 Flowchart

![Alt text](/image/flow.png)
* * *
### 순서
1) 악성코드는 서버에 10004번 포트로 'IMHACKER_10자리 숫자' 메시지를 UDP 통신으로 전송한다.

2) C&C 서버로 부터 공격 대상자 IP와 PORT 번호를 받고 공격지에 UDP Flooding 공격을 수행한다.

=> 10자리 숫자를 10번 반복해서 전송

3) 악성코드는 단독으로 실행하는 EXE 파일로 작성

4) 악성코드의 분석가를 방해하기 위해 EXE 파일을 난독화하였다.
![Alt text](/image/udp.png)
![Alt text](/image/peid.png)



### 참고
* 외부링크: <https://t-okk.tistory.com/59/>
