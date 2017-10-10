# KuKu Meter
  1. Client ID와 Client Secret key 생성
  > 1) Enertalk Developers사이트 접속 및 계정 생성

  > 2) ‘MY APPS’의 ‘Create Apps’에서 생성 및 Redirect URL 입력
  https://graph.api.smartthings.com/oauth/callback

2. SmartThings IDE에 SmartApp과 DTH 설치 및 설정
  * 직접 소스를 카피해서 SmartThings IDE SmartApp과 DTH 생성
  * SmartThings IDE GitHub Repository를 통한 SmartApp과 DTH 생성(이 방법으로 설명진행)

  > https://github.com/turlvo/KuKuMeter

  > 1) SmartThings IDE ‘My SmartApps’ 에서 ‘Settings’ 선택, ‘Add new repository’ 선택 후 아래와 같이 입력

    * Owner : turlvo
    * Name : KuKuMeter
    * Branch : master



  > 2) ‘Update from Repo’에서 ‘1)’에서 추가한 ‘KuKu Meter’ 선택


  > 3) 아래와 같이 ‘KuKu Meter’ SmartApp을 선택, ‘Publish’ 선택후 ‘Execute Update’선택


  > 4) 설치 한 ‘KuKu Meter’ SmartApp 선택, ‘App Settings’

  > > 4-1) Settings에 ‘1)’에서 생성 한 Client ID와 Client Secret입력
  
  > > 4-2) ‘OAuth’ Enable



  > 5) ‘My Device Handler’메뉴에서도 ‘2)’와 같이 ‘KuKu
  talk’용 DTH 설치


3. SmartThings Application에 ‘KuKu Meter’ 설치
  > 1) SmartThings Application -> ‘Automation’ -> ‘SmartApp’ -> ‘Add a SmartApp’ 진입
  > 2) ‘KuKu Meter’ 선택
  > 3) ‘Enertalk’ 인증 진행(ID, Password)
  > 4) 인증 완료 후 계정 정보 확인 후 최종 ‘Done’ 클릭


