# cloud-edge-mgnt 컴파일 방법

## 사전 환경
* spring boot 설치 필요
  * 언어: java8+
  * 빌드 도구: maven
  * IDE: Intelij
  
## spring boot 시작하기  
* spring boot project 생성
* http://start.spring.io/ 에서 생성 또는 Intelij 내 프로젝트 생성
* import Project
  * maven 플러그인 설치 되어 있어야 함 

## Maven dependency 추가
*  pom.xml 에 Maven dependency를 추가한 후 해당 Library를 이용하기 위해서는 추가
*  Maven > importing 에서 Import Maven projects automatically 체크를 통한 자동 update
  
## Reimport All maven Projects
### maven update 
intelij 실행 후  , Maven update
* root 선택
  * clean -> complie -> install 순으로 update (권장)
  
## Generate Sources and Update Folders For All Projects 후  Application 실행 
### Application 컴파일
 application 각각 실행 
* ApiOpenstackApplication 
* ServiceRegistryApplication
* GatewayApplication
* ClientApplication
