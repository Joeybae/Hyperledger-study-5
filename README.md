# Hyperledger-study-5

하이퍼레져 앱 만들기 실습 5일차 - 이론 공부

2019년 블록체인 공공 시범사업

과학기술정보통신부(장관 유영민, 과기정통부)와 한국인터넷진흥원(원장 김석환, KISA)이 블록체인 확산을 이끌기 위해서 올해 진행하는 ‘2019년 블록체인 공공선도 시범사업’ 세부 내용이 5월 29일 모두 공개됨

1. 탈중앙화 기부 플랫폼 – 이포넷
  기부 서비스 시장성 및 블록체인 기술 신뢰성을 확보하기 위한 6가지 전략
  - 개방형 캠페인 네트워크
  - 기부 연계 커머스
  - 참여형 캠페인 거버넌스
  - 퀄리티 켐페인 큐레이션
  - 저지연 고생존 블록체인 원장
  - 안전 연동 블록체인 결제 시스템
  
2. 블록체인ID 인증 서비스 – SK텔레콤
  잦은 개인정보 유출 사고로 개인정보보호 방식이 바뀌고 있고, 블록체인 기반의 자기주권 신원 모델(Self Sovereign Identity, SSI)으로 개인정보 보호방법 3가지
  - 자기주권 신원지갑
  - 스타트업 투자플랫폼
  - 대학 제증명 서비스
  
3. 블록체인 중고차 플랫폼 – 현대오토에버
  각종 차량 이력정보(인증, 평가, 점검 등)를 블록체인에 기록해 위변조를 막고 중고차 거래 및 관리의 신뢰성을 높이는 것을 목표로 한다.
  
4. 블록체인 국가기록관리 플랫폼 – 토피도
  블록체인 기술을 활용하면 행정전자문서가 생성된 후 실시간으로 관계 기관과 공유를 거쳐 진본성 검증이 가능
  
5. 블록체인 REC(신·재생에너지공급인증서, Renewable Energy Certificate) 거래 서비스 – 엔텔스
  업무 절차 간소화 및 인건비 절감, 대국민 행정서비스 효율화와 정보의 신뢰성을 확보
  
6. 블록체인 탄소배출권 이력관리 – SGA블록체인
  블록체인 기술을 활용해 탄소배출권 이력관리를 투명하게 관리해서 신뢰성과 보안성을 높이고 이중거래를 방지한다면 배출권 거래가 활성화
  
출처 : https://www.coindeskkorea.com/48088/

현재 블록체인 공공기관 시범사업에 선정된 이유로는 '1) 신원확인, 2) 위변조 방지, 3) 높은 신뢰성, 4) 실시간 업무 공유' 로 생각된다.

------------------------------------------------------------------------------------------------------------------------------

블록체인과 DB의 차이점

데이터 저장 및 관리 인프라

1. 분산원장 - 위변조 불가능

  블록체인 기술은 변경할 수 없는 트랜잭션 기록을 생성해 분산형 원장에 보존하는데 최적화된 기술이며, 같은 체인에 있는 모든 당사자는 동일한 사본을 보유하고 이에 액세스할 수 있다. 한편, 이는 체인에 있는 모든 당사자에 대해서 불역성, 보안, 프라이버시, 감사 기능을 제공한다.
  단일 관리자가 있는 데이터베이스와는 달리 블록체인은 관리자가 여러 명이며 각자가 원장의 사본을 보유하고 있다.
  
2. 스마트 계약 - 허가형 블록체인(하이퍼레저)

  스마트 계약은 투명하고 사전에 결정된 규칙을 실행하여 불필요한 검증 및 중간 과정을 없애서 효율적으로 활용 가능.

허가형 블록체인의 장점 : 허가형 블록체인은 기관들 사이에 충분한 신뢰만 있으면 블록체인에 참여할 대상을 결정할 수 있고, 그들이 네트워크에 합류한 후에는 블록체인이 참여자들의 정직성을 유지한다. 허가형 블록체인 네트워크를 통해 기관들 사이에서 가치의 원자적 이동이 가능하며, 여기에서 둘 다 트랜잭션 발생 전과 후의 원장의 상태에 대해 즉시 동의할 수 있다

출처 : http://www.itworld.co.kr/news/118347#csidxdf87004315821ac8fa2537c184bff3a 
