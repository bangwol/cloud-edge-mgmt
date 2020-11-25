# cloud-edge-mgnt 컴파일 방법

## 사전 환경
* spring boot 설치 필요
  * 언어: java8+
  * 빌드 도구: maven (https://maven.apache.org/download.cgi)
  * IDE: Intelij
  
## spring boot 시작하기  
* spring boot project 생성
* http://start.spring.io/ 에서 생성 또는 Intelij 내 프로젝트 생성
* import Project
  * maven 플러그인 설치 되어 있어야 함 

## Maven dependency 추가
*  Maven dependency를 추가를 위해 pom.xml 에 해당 Library를 추가하여 설치 가능
*  프로젝트 생성 시 Maven > importing 에서 Import Maven projects automatically 체크를 통한 자동 update 하도록 설정 가능 
 
## Reimport All maven Projects 후 maven update 실행 
### maven update 
intelij 실행 후 , 오른쪽 Maven 선택
* root 선택 (프로젝트 전체 update) 
  * clean -> complie -> install 순으로 maven update (권장)
  
## Generate Sources and Update Folders For All Projects 
* 각 application build 후 에러 없는지 확인후 Aapplicatin 실행 

### Application 컴파일 및 실행 
* spring boot application 각각 실행 
 * ApiOpenstackApplication 실행
 * ServiceRegistryApplication 실행
 * GatewayApplication 실행 
 * ClientApplication 실행 
