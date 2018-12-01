# 1.안드로이드(Android)
## 1.1 개요
   안드로이드(Android)는 리눅스 커널을 기반으로 구글에서 제작한 스마트폰과 같은 플랫폼의 모바일 운영 체제와 미들웨어 및 중요 애플리케이션이 포함된 소프트웨어 집합이다. 구글은 새로운 운영체제의 버전 공개와 동시에 소스를 공개하고 있다. 이렇게 공개된 소스를 AOSP라고 한다.  
   안드로이드(86%)와 iOS 점유율(14%)을 소수점 아래에서 반올림하고 합치면 100%이다. 나머지 모바일 운영 체제는 의미 없는 점유율(0.1% 이하)만을 차지하고 있다. 스마트폰 OS 점유율 3위인 윈도우의 점유율조차 0.1%까지 떨어져서 결국 MS에서도 모바일 운영 체제 시장 포기를 선언하였고, 모바일 OS 시장은 안드로이드와 iOS로 개편이 끝났다.
## 1.2 역사
2005년 7월에 구글은 미국 캘리포니아주의 팔로알토에 위치한 작은 안드로이드사를 인수하였다. 안드로이드사는 앤디 루빈이 세운 업체이다.

2007년 11월 5일에 텍사스 인스트루먼트, 브로드컴 코퍼레이션, 구글, HTC, 인텔, LG전자, 마벨 테크놀로지 그룹, 모토로라, 엔비디아, 퀄컴, 삼성전자, 스프린트 넥스텔, T-모바일의 몇몇 회사로 구성된 컨소시엄인 오픈 핸드셋 얼라이언스(OHA)가 모바일 기기의 공개 표준을 개발하는 것을 목표로 결성되었다.[1] 또한 OHA는 리눅스 커널 2.6에서 빌드된 그들의 첫 번째 모바일 기기 플랫폼 결과물인 안드로이드를 발표하였다.

2008년 10월 21일에 안드로이드가 오픈 소스로 선언되었다. 구글은 네트워크와 텔레폰 스택을 포함하는 완전한 소스 코드를 아파치 라이선스로 공개하였다.

2008년 12월 9일에 ARM 홀딩스, 아세로스(Atheros Communications), 에이수스, 가르민, 소프트뱅크, 소니 에릭슨, 도시바, 보다폰으로 구성된 새로운 14개의 멤버가 안드로이드 프로젝트에 참여하였다.

2014년 10월 16일 안드로이드 5.0 버전 발표와 함께 기존의 달빅 가상 머신을 안드로이드 런타임으로 대체하였다.

## 1.3 특징
  Android의 기본 사용자 인터페이스는 주로 직접 조작을 기반으로 한다. 가상 키보드와 함께 화면상의 개체를 조작하기 위해 스와핑, 탭핑, 핀치 및 역핀칭과 같은 실제 동작에 느슨하게 대응하는 터치 입력을 사용하나. 게임 컨트롤러와 실물 크기의 키보드는 블루투스 또는 USB를 통해 지원된다. 사용자 입력에 대한 응답은 즉시 이루어지도록 설계되었고 유동적인 터치 인터페이스를 제공하며, 종종 기기의 진동 기능을 사용하여 사용자에게 촉각 피드백을 제공한다. 가속도계, 자이로스코프 및 근접 센서와 같은 내부 하드웨어는 추가적인 사용자 작업에 응답하기 위해 일부 애플리케이션에서 사용된다.  
  메모리 관리에서, Android 기기는 보통 배터리로 구동되기 때문에 전력 소비를 최소한으로 유지하기 위한 프로세스를 관리하도록 설계되었다. 응용 프로그램을 사용하지 않는 경우 시스템이 작동을 중지하여 하지만 배터리 전원 또는 CPU 리소스를 사용하지 않도록 . Android는 메모리에 저장된 애플리케이션을 자동으로 관리하며, 메모리가 부족하면 시스템이 가장 오랜 시간 동안 비활성 상태였던 프로세스부터 보이지 않게 자동으로 닫힌다.
  
## 1.4 버전
  코드네임은 A부터 시작하여 알파벳순으로 지어지며, 그 이름이 모두 디저트 이름이다.
  
  ![default](https://user-images.githubusercontent.com/43702356/49329878-4fbfc680-f5c9-11e8-88da-b6ac5804028a.PNG)

## 1.5 장점
1. Flash를 지원하기 때문에 각종 동영상이나 창작물을 PC와 같이 볼 수 있다.
2. 위젯을 지원하기 때문에 한 눈에 여러 정보를 확인할 수 잇다.
3. 각종 코덱을 지원하기 때문에 대부분의 동양싱을 오랜 시간 변환없이 바로 시청할 수 있다. 
4. 오픈 소스를 지원하기 때문에 수정 및 배포가 가능하여 자유도가 뛰어나 특정 보안 상황에 맞춰 제작할 수 있다.
5. JAVA기반이기 때문에 제품의 범위가 넓다.
6. 리눅스 커널을 이용하기 때문에 C언어 개발자도 개발이 가능하다.
  
# 2.NGINX
## 2.1 개요
  2002년부터 러시아의 프로그래머 이고르 시쇼브(Игорь Сысоев)가 Apache HTTPd를 코딩하다 Apache의 C10K 문제를 보고, 이를 극복하기 위해서 네이티브 Win32 환경에도 돌아갈 무설치 웹 서버 데몬 프로그램에 대한 개발을 시작하여 2004년 스푸트니크 1호 발사일에 발표한 오픈 소스 웹 서버 프로그램. 현재 이고르 시쇼브와 그가 설립한 회사인 nginx.Inc.가 이 프로젝트를 운영중에 있다. 목표는 가벼우면서도 강력한 프로그램이라고 한다. HTTP와 리버스 프록시, IMAP/POP3 등의 서버 구동이 가능하다. Java 서블릿은 대개 Apache의 톰캣을 연동해서 구동하고, PHP의 경우 PHP-FPM(FastCGI Process Manager)을 연동해서 구동한다.
## 2.2 역사 
  Gor Sysoev는 2002년에 Nginx의 개발을 시작했다.원래 Nginx는 C10k 문제를 해결하고 2008년 9월까지 매일 5억 건의 요청을 처리하는 램버 검색엔진과 포털을 포함한 웹 사이트의 요구를 충족하기 위해 개발되었다.

Sysoev는 2011년 7월 상용 제품과 소프트웨어 지원을 제공하기 위해 같은 이름의 회사를 설립. 이 회사의 주요 사업장은 캘리포니아주 샌프란시스코이며 영국령 버진아일랜드에 법적으로 통합되어 있다.

2011년 10월 Nginx는 Michael Dell의 벤처 펀드인 BV캐피털, Runa Capital 및 MSD Capital로부터 300만 달러를 모금. Nginx를 생산하는데 사용하는 회사에 대한 상업적 지원 옵션을 발표했다. Nginx는 2012년 2월에 상업적인 지원을 제공하고 2013년 8월에 Nginx Plus 가입 비용을 지불.

지원 패키지는 설치, 구성, 성능 향상 등에 중점을 두며 지원에는 주요 변경 사항, 보안 패치, 업데이트 및 패치에 대한 사전 알림을 포함.

WordPress 개발자 Automatic Inc.와 컨텐츠 제공 네트워크 공급업체 MaxCDN은 2014년 초로 예정된 Google의 SPDY 버전 3.1 업데이트에 대한 후원 파트너가 되었다. 또한 Nginx는 고객이 맞춤 구성 또는 추가 기능을 추가할 수 있도록 컨설팅 서비스를 제공.

2013년 10월 Nginx는 New Enterprise Associates가 주도하는 1000만 달러 규모의 B시리즈 투자 라운드를 개최했다. 이전 투자자는 물론 Box.com.의 CEO 겸 설립자인 Aaron Levie도 이 라운드에 포함되어 있다.

2014년 12월, Nginx는 e.벤처(이전의 BV Capital), Runa Capital, Index Ventures, N.S.에서 참석한 가운데 뉴 Enterprise Associatter가 이끄는 2천만 달러 시리즈 B1 라운드를 개최했다.

2017년 10월 Nginx Inc.는 Nginx에 대한 모니터링 및 분석 기능을 제공하는 일반 Nginx Amplify SaaS를 발표.

2017년 9월 Nginx는 API 게이트웨이 NGINX Plus를 기반으로 하는 API 관리 툴 NGINX 컨트롤러를 발표.

2018년 6월 Nginx는 Goldman Sachs가 이끄는 시리즈 C 펀딩에서 4,300만 달러를 모금하여 "기업의 애플리케이션 현대화와 디지털 혁신 가속화"를 실현.

## 2.3 인기도
  Netcraft의 2016년 11월 웹 서버 설문조사에 따르면 Nginx는 모든 active 사이트(조사 사이트의 18.22%)와 상위 백만 사이트(27.83%)에서 두 번째로 널리 사용되는 웹 서버인 것으로 확인되었다. W3테크놀로지는 상위 100만개 웹사이트의 37.7%, 상위 10만개 웹사이트의 49.7%, 상위 10,000개 웹사이트의 57.0%에 의해 사용되었다. BuiltWith에 따르면, Nginx는 상위 10,000개 웹사이트의 38.2%에 사용되고 있으며, 상위 1만, 10만, 100만개 부문에서의 성장은 증가하였다고 한다. 2018년 Docker 사용을 조사한 결과 Nginx는 Docker 컨테이너에서 가장 흔히 사용되는 기술이라고 다.
## 2.4 HTTP 프록시와 웹 서버 기능
1. 정적 파일과 인덱스 파일 표현, 자동 인덱싱 기능.  
2. 캐싱을 통한 리버스 프록시  
3. 로드 밸런싱  
4. 고장 진단  
5. SSL 지원  
6. 캐싱을 통한 FastCGI 지원  
7. Name-, IP-기반 가상서버  
8. FLV 스트리밍  
9. MP4 스트리밍 모듈을 이용한 MP4 스트리밍  
10. 웹페이지 접근 인증  
11. gzip 압축  
12. 10000개의 동시 접속을 처리할 수 있는 능력  
13. URL 다시쓰기 (URL rewriting)  
14. 맞춤 로깅  
15. 서버 사이드 기능 포함  
16. WebDAV (HTTP의 확장으로, WWW서버에 저장된 문서와 파일을 편집하고 관리하는 사용자들 사이에 협업을 손쉽게 만들어 준다.)
## 2.5 Apache와의 비교
  Nginx는 Apache 웹 서버를 능가한다는 명백한 목표를 가지고 제작되었다. 고정 파일을 제공하는 즉시 사용 가능한 Nginx는 Apache보다 훨씬 적은 메모리를 사용하며 초당 약 4배 더 많은 요청을 처리할 수 있다. 반면에 windows 구성 시스템에서는 안정성이 떨어지는 것으로 알려져 있는 반면 Apache는 완전한 지원을 받는다. 이러한 성능 향상은 파일별로 시스템 전체 액세스 설정을 재정의할 수 있는 기능과 같이 유연성이 떨어지는 비용에서 발생한다(Apache는 .htaccess 파일로 이를 수행하지만 Nginx에는 이러한 기능이 내장되어 있지 않다).   
  이전에는 nginx에 타사 모듈을 추가하려면 정적 연결 모듈을 사용하여 소스에서 애플리케이션을 다시 컴파일해야 했다. 이는 2016년 2월 1.9.11 버전에서 일부 극복되었으며 동적 모듈 로딩이 추가되었습니다. 그러나 이 모듈들은 여전히 nginx와 동시에 컴파일되어야 하며, 모든 모듈이 이 시스템과 양립할 수 있는 것은 아니며, 일부 모듈들은 이전의 정적 연결 프로세스를 필요로 한다.
# 3.Redis
## 3.1 개요
  레디스(Redis)는 Remote Dictionary Server의 약자로서, "키값" 구조의 비정형 데이터를 저장하고 관리하기 위한 오픈 소스 기반의 비관계형 데이터베이스 관리 시스템(DBMS)이다. 2009년 살바토르 산필리포(Salvatore Sanfilippo)가 처음 개발했다. 2015년부터 Redis Labs가 지원하고 있다. 모든 데이터를 메모리로 불러와서 처리하는 메모리 기반 DBMS이다. BSD 라이선스를 따른다. DB-Engines.com의 월간 랭킹에 따르면, 레디스는 가장 인기 있는 키값 저장소이다
## 3.2 역사
  이 프로젝트는 원래 Redis의 개발자인, Antirez라고도 알려진 Salfillifelo가 실시간 웹 로그 분석기를 개발하면서 이탈리아 스타트업의 확장성을 향상시키려고 노력하면서 시작되었다. 기존 데이터베이스 시스템을 사용하여 특정 워크로드를 확장하는 데 심각한 문제가 발생한 후, Sanfillifo는 Tcl에 Redis의 첫 번째 개념 증명 버전을 프로토타입화하기 시작했다.나중에 Sanfillifilo는 이 시제품을 C 언어로 번역하고 첫 번째 데이터 유형을 구현하였다. 이것이 바로 list이다. 몇 주 동안 내부적으로 프로젝트를 성공적으로 사용한 후, Salfillifelo는 해커 뉴스에서 이 프로젝트를 발표하면서 소스를 열기로 결정했습니다. 이 프로젝트는 특히 루비 커뮤니티에서 관심을 끌기 시작했고 GitHub와 Instagram은 이 프로젝트를 처음 채택한 회사 중 하나였다. Sanfillifo는 2010년 3월에 VMware에 의해 고용되었습니다. 2013년 5월, Redis는 Pivotal Software(VMware 스핀오프)의 후원을 받았으며 2015년 6월에 개발에 Redis Labs가 참여하였다.
# 4.Maria DB
## 4.1 개요
