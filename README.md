# KGC_project
영업 마케팅 차세대 1차 프로젝트 (22.9 ~ 23.6) - 약 70억

총 3차로 3년 예정 -> 총합 330억에서 300억 비용 예산 산정이나, 2차/3차 미정

'''
영업 마케팅 차세대 프로젝트 수행 중 관련 내용을 기록합니다 (정신없이 뒤늦게 시작한 기록..)

내 역할은.. 신입으로 프로젝트 전반적인 흐름을 배울 것 
인력관리, 범위관리, 위헙/이슈관리, 신규 인력 투입 승인 요청 진행, 주간업무보고 취합, 주간업무보고 요약본 작성, 월간업무보고서 취합, PMS 등록 파일 검토, 회의록 관리, 인력 프로파일 관리, 보안점검 책임자, 산출물 관리 진행..

업무 분장표
UI/UX, 인터페이스, 문서관리
- 고객 WEB/Back Office UI/U, 사용자 화면 흐름 검토
- 인터페이스 As-Is, To-Be 변화 관리
- AO 분석계 시스템 연동 : AO -> 분석계 실적데이터 전송
- 문자발송 관리 : 계정,정산부서, 발송 모니터링
- 타사 정책/사례 비교 검토
- 상담시스템 연계 : 회원조회/수정 이력관리
- 현업 교육, 매뉴얼 관리

현재는 1차 프로젝트로 완료될 회원, 포인트 시스템의 서브 도메인 선정중
1. 회원, 포인트 시스템
   - mps.kgc.co.kr (members point system)
   - jms.kgc.co.kr (jung kwan jang members system)
   - members.kgc.co.kr     -> 후보 유력
  
2. 대시보드(의사결정 시스템)
   - dss.kgc.co.kr (decision support system)
   - bi.kgc.co.kr (businesss intelligence)
   - eyeanly.kgc.co.kr


  PMS 시스템에서 WBS 등 매일 회의에 걸쳐서 차세대 프로젝트 진행 중입니다.

PMS 진척율 관련 - 각 파트별 가중치(가중치 총 100%기준), 계획 진척율, 실적진척율, 달성률 현황 체크
0. 프로젝트 관리  - 가중치 9%
1. BO 회원        - 9%
2. BO 포인트      - 9%
3. 기준정보       - 9%
4. FO 회원        - 9%
5. 대응개발       - 9%
6. 마이그레이션   - 9%
7. 인프라(AA)     - 5%
8. 인프라(TA)     - 5%
9. 분석계         - 9%
10. 기획          - 9%
11. 대시보드      - 5%
12. 공통(PM)      - 4%

-----------------------------------------------------------------------------------------------------------
```
[WBS]
0. 프로젝트 관리
1. 프로젝트 착수 및 계획수립
  1.1 프로젝트 착수
   1.1.1 수행환경세팅
  1.2 프로젝트 범위정의
   1.2.1 업무범위정의
     1.2.1.1 업무범위  - 산출물:사업수행계획표
     1.2.1.2 관업대비표 - 산출물: 과업대비표
   1.2.2 개발전략 수립
     1.2.2.1 개발전략 - 산출물 : 사업수행계획서
   1.2.3 WBS 정의
     1.2.3.1 프로젝트 WBS - 산출물 : 프로젝트 WBS
   1.2.4 산출물 테일러링 - 산출물 : 표준프로세스테일러링내역서
  1.3 프로젝트 계획 수립
   1.3.1 일정관리 계획수립 - 산출물 : 프로젝트WBS, 사업수행계획서
   1.3.2 프로젝트 조직 구성 - 산출물 : 사업수행계획서
   1.3.3 품질관리 게획수립 - 산출물 : 품질관리계획서
   1.3.4 의사소통 게획수립 - 산출물 : 사업수행계획서
   1.3.5 교육훈련 계획수립 - 산출물 : 교육훈련계획서
   1.3.6 위험관리 계획수립 - 산출물 : 사업수행게획서, 이슈및위험관리대장
   1.3.7 변경관리 계획수립 - 산출물 : 사업수행계획서
   1.3.8 형상관리 계획수립 - 산출물 : 형상관리계획서
   1.3.9 보안관리 계획수립 - 산출물 : 보안관리계획서
   1.3.10 테스트 계획수립 - 산출물 : 사업수행계획서, 이슈및위험관리대장
   1.3.11 인력관리 계획수립 - 산출물 : 사업수행계획서
   1.3.12 범위관리 계획수립 - 산출물 : 사업수행계획서
  1.4 프로젝트 표준 및 절차정의
   1.4.1 프로젝트 표준 및 절차 정의 : 프로젝트 문서 표준
   1.4.2 산출물 표준 정의 : 기본 템플릿, 산출물 목록
  1.5 프로젝트 계획확정
   1.5.1 프로젝트 계획승인 : 사업수행계획서
   1.5.2 프로젝트 착수보고 : 착수보고서
3. 프로젝트 수행 및 통제
  2.1 성과측정 및 보고
   2.1.1 주간보고
    2.1.1.1 주간보고(1주차 ~ 40주차까지 : 40주차는 종료보고서로 대체)
   2.1.2 월간보고
   2.1.3 중간보고1차(분석단계 리뷰)
   2.1.4 중간보고2차(분석/설계단계 리뷰)
   2.1.5 종료보고
  2.2 이슈 및 위험관리 : 이슈및위험관리대장
  2.3 품질관리
   2.3.1 산출물 품질검토 : 결함및시정조치목록
   2.3.2 QA점검 : 품질점검계획서, 품질점검결과서
    2.3.2.1 QA 1차 점검
     2.3.2.1.1 상세계획수립 및 공지
     2.3.2.1.2 QA 심사 실시
     2.3.2.1.3 조치 계획 수립 및 수행
     2.3.2.1.4 조치 결과확인 및 보고
    2.3.2.2 QA 2차 점검
     2.3.2.2.1 상세계획수립 및 공지
     2.3.2.2.2 QA 심사 실시
     2.3.2.2.3 조치 계획 수립 및 수행
     2.3.2.2.4 조치 결과확인 및 보고
    2.3.2.3 QA 3차 점검
     2.3.2.3.1 상세계획수립 및 공지
     2.3.2.3.2 QA 심사 실시
     2.3.2.3.3 조치 계획 수립 및 수행
     2.3.2.3.4 조치 결과확인 및 보고
   2.3.3 감리
    2.3.3.1 1차 감리
     2.3.3.1.1 감리실시
     2.3.3.1.2 조치계획수립 및 수행
     2.3.3.1.3 조치결과확인 및 보고
    2.3.3.1 2차 감리
     2.3.3.2.1 감리실시
     2.3.3.2.2 조치계획수립 및 수행
     2.3.3.2.3 조치결과확인 및 보고
    2.3.3.1 3차 감리
     2.3.3.3.1 감리실시
     2.3.3.3.2 조치계획수립 및 수행
     2.3.3.3.3 조치결과확인 및 보고
  2.4 보안관리
   2.4.1 보안교육
   2.4.2 보안점검 - (12월 ~ 6월)
  2.5 교육관리 : 교육결과서 
   2.5.1 사용자교육
    2.5.1.1 사업개요 및 프로젝트 착수 교육
    2.5.1.2 개발방법론
    2.5.1.3 통합관리도구
   2.5.2 개발자교육
    2.5.2.1 표준화 교육
    2.5.2.2 도입 솔루션
  2.6 형상관리 : 형상항목관리대장, 백업관리대장
  2.7 범위관리 : 과업대비표
  2.8 프로젝트 변경관리 : 변경요청서, 변경관리대장
  2.9 인력관리 : 투입인력현황, 주말인력투입보고(주간보고서)
4. 프로젝트 종료
  3.1 종료계획수립
  3.2 시스템 인수인계
   3.2.1 시스템 인수인계 계획수립 : 인수인계계획서
   3.2.2 시스템 인수인계 실시 : 인수인계계획서
  3.3 최종 고객검수 및 종료
   3.3.1 최종검수획득




   3.3.2 프로젝트 종료
   3.3.3 최종검수요청 : 검수확인서
  3.4 검수
   3.4.1 중간검수
   3.4.2 최종검수

```


--------------------------------------------------------------------------------------------------------------------------
* IT 프로젝트 전과정 (8단계로 구분)
   1. 프로젝트 제안 및 수주
       - 고객사 사전 분석 (RFI) : 고객사가 프로젝트 발주를 위해 사전 정보 수집하는 단계 
       - 사업공고 및 제안요청 (RFP) : 고객사의 RFP 기반의 제안요청
       - 제안 및 견적 (RFQ)  : 고객사 사업 공고에 따른 제안 및 견적 작업, 제안 발표
       - 낙찰(계약) : 업체 선정 및 계약
   2. 프로젝트 계획 및 시작
       - 팀구성 : 내부 및 외주 포함 팀 구성
       - 프로젝트 진행 전반 계획 : 현업 TFT와 진행 계획 
       - 기본 진행 일정 계획 : 주요 업무 단위별 러프한 일정 계획 
       - 프로젝트 본격 시작 : 착수보고 (관련자 사업보고, 업무요청, 진행 방향등 공유)
   3. 기획
       - 요구사항 분석
       - 개발 기능 정의 (이후 WBS 상세 일정) 
       - 프로세스정의
       - 상세화면 기획
   4. 디자인
       - 디자인 컨셉 확인
       - 디자인 시안 작업
       - 디자인 시안 확정 및 Develop
       - 전체 화면 디자인 작업 
   5. 퍼블리싱
       - 일정에 따른 퍼블리싱
       - 퍼블리싱 보완 및 지원
   6. 개발
       - (1-5과정중)서버-네트워크 환경 구성
       - (1-5과정중)개발 환경 구성  
   7. 테스트
       - 테스트 케이스 작성
       - 테스트 시나리오 작성
       - 단위테스트 및 보완
       - 통합테스트 및 보완
   8. 오픈 안정화
       - 사전교육 (사용자, 관리자 메뉴얼 기반)
       - 오픈준비 (데이터전환 계획, 배포 계획등 이행계획 수립)
       - 오픈 
       - 안정화 지원 및 검수

​
