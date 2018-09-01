# SETALab
# AuLoRa

오로라 사용을 위해서는 온라인 라이센스 구매가 필요합니다. 

  2018년 오로라 온라인 라이센스 사용료
	
  1개월 : 30만원  1년 : 300만원
	
  Contact :  www.setalab.com help@setalab.com 
  오로라를 이용한 로라 기술 교육 동영상: 
    https://youtu.be/MoPm72SUUzI 
    https://youtu.be/bTfFbvgL5HY
  

AuLoRa 1.2 버전 업데이트 2018.7.12
1. data가 200개가 넘을 경우 heap 오류 수정  
2. txpk tmst dword -> double로 확장 ( 4byte -> 8byte)
3. log save 기능 추가 
4. data가 200개가 넘을 때 버퍼 오류 수정
5. 인증 루틴 수정 (온라인 -> 오프라인)
6. RX1 windowdelay 오류 수정
7. RX2 Down API 추가
8. Class C 지원
9. DR5 max data down 오류 수정 
-------------------------------------------
  
AuLoRa 1.1 버전 업데이트 
1. 인증 서버 변경
2. 로그 레벨 변경 API 추가 :
    SrvSetLogMode(loglevel); // 0 : all, 1: correct data ony, 2 : correc data + MIC error
3. Down FCnt 설정 API 추가:
   SrvSetParam("DOWNFCOUNT",		"005A"); // 0x005A
4. Log file save 기능 추가
5. Mac Command Hexa 처리 오류 수정
