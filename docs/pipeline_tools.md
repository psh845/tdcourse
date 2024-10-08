# 프로젝트 매니징 파이프라인 툴

회사는 진행하는 프로젝트를 추적, 관리하기 위해서 프로젝트 매니징 툴을 사용합니다.
필요에 따라서는 구매하기도 하고 자체적으로 제작하기도 합니다.

구매한 툴 또는 내부에서 제작된 파이프라인툴은 그래픽스툴들과 연결하여 정보를 가지고 오거나 정보를 셋팅하는 기능을 설정해서 많이 사용합니다.
이 때 많이 사용하는 언어는 Python 입니다.

원하는 회사가 있다면 그 회사에서 사용하는 파이프라인툴 + 파이프라인툴 Python API를 조금은 공부하고 취업준비를 한다면 많은 도움이 될 것 입니다.
이번 시간에는 시장에서 사용되고 있는 프로젝트 매니징 파이프라인 툴에 대해서 간략히 알아보겠습니다.

## 상용툴

### Shotgrid

![shotgrid](https://damassets.autodesk.net/content/dam/autodesk/www/products/shotgrid/fy23/features/images/key-features-of-shotgrid-large-1920x976.jpg)


국내 대규모 업체들은 shotgrid을 많이 사용하고 있습니다.
- 사용업체 : Weta, Framestore, Mackevision, Pixomondo, Westworld, [포스](https://www.awn.com/news/2018-shotgrid-pipeline-award-winners-announced),
- 비용: 월 45,000원 / 1인
- 홈페이지 : https://www.shotgridsoftware.com
- DB : PostgreSQL
- API : https://github.com/shotgridsoftware

### Ftrack

![ftrack](https://i.ytimg.com/vi/PBjgVmQfZus/maxresdefault.jpg)
- 홈페이지 : https://www.ftrack.com/en/
- DB : MySQL
- API : https://bitbucket.org/ftrack/ftrack-python-api
- python API : http://ftrack-python-api.rtd.ftrack.com/en/stable/introduction.html


### Kitsu

- 정책: 유료 / 월 30명까지 한달에 800달러
- 홈페이지: https://www.cg-wire.com/en/kitsu.html
- DB: 
- API: 지원

### Wormhole2

국내 C2Monster사에서 제작되는 파이프라인툴 입니다.

- 홈페이지 : http://www.wormholepipeline.com


#### File Maker Pro

간단하게 비 프로그래머가 App을 만들 수 있는 도구입니다.
많은 조직, 회사에서 이 툴을 이용해서 파이프라인툴을 만드는 경우도 있습니다.

- 홈페이지 : https://www.filemaker.com

## 오픈소스 & 무료툴

### OpenPipelineIO

![OpenPipelineIO_1](https://github.com/lazypic/OpenPipelineIO/raw/main/figures/screenshot.png)
![OpenPipelineIO_2](https://github.com/lazypic/OpenPipelineIO/raw/main/figures/review.png)

- 정책 : 오픈소스
- 홈페이지: https://github.com/lazypic/OpenPipelineIO
- DB: mongoDB
- API: RestAPI 지원

### Openpype

- 정책: 오픈소스
- 홈페이지: https://openpype.io/
- DB: mongoDB
- API: 지원


### Tactic

![tactic](https://i.ytimg.com/vi/aqj4Zx2ly98/maxresdefault.jpg)
- 정책 : 부분유료
- 홈페이지 : http://www.southpawtech.com
- 사용업체 : [덱스터](http://www.southpawtech.com/customers/dexter-digital/)
- DB : PostgreSQL
- API : https://github.com/Southpaw-TACTIC/TACTIC

### Kitsu

- 웹사이트: https://www.cg-wire.com/
- 홍보 영상: https://youtu.be/2HNnFffAADU
- 가격 정책: https://www.cg-wire.com/en/pricing.html
- 리눅스 서버 설치방법: https://youtu.be/QtFzQMYZSDc

### Prism

![prism](https://prism-pipeline.com/wp-content/uploads/2018/04/2018-04-04_1735-1.png)
간단한 파일베이스 오픈소스 파이프라인 툴입니다.

- 홈페이지 : https://prism-pipeline.com

### Cage

- 홈페이지 : https://cageapp.com/

### Attract

![attract](https://i.ytimg.com/vi/b9x1rlyyt_o/maxresdefault.jpg)
Blender Cloud에서 사용되는 오픈소스 파이프라인툴 입니다.

- 사용언어 : PHP
- 홈페이지 https://attract.studio
- 서비스 페이지 : https://cloud.blender.org/attract/

## 기타툴

- http://www.helgaproject.org
- https://www.binfire.com
- http://www.basecamp.com
- http://www.wrike.com
- http://www.proofhub.com


## 사내 인하우스툴

보통 인하우스툴은 외부에 공개하지 않지만 일부 회사에서 내부 상황에 맞도록 프로젝트 매니징 파이프라인 툴을 개발하여 사용합니다.
