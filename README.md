# flyway-h2
H2, flyway 사용해서 로컬 디비 관리

사용 도구
ide - intellij
build tool - gradle 3.0
framework - spring boot
db - h2 1.4.191
db version control - flyway-release:4.0.3

git hub
 https://github.com/redjun00/flyway-h2

redjun00/flyway-h2
flyway-h2 - H2, flyway 사용해서 로컬 디비 관리
github.com


git hub 소스에 주석으로 적어놓은 것 + 
h2 db가 정상적으로 변경되는 것을 확인하려면 console 창으로 확인하는 방법이 있고 ide에서 확인할 수 있는 방법이 있다.

intellij에서 확인하는 방법
아래 url은 eclipse에서 확인하는 방법인데 이것과 거의 유사하다.
아래 url을 참고해서 database를 intellij 오른쪽 창에 추가한 뒤 database에서 우클릭하면 open console 메뉴가 있고 콘솔을 열어서 거기에 sql 명령을 치면 아래 창에 결과가 보인다.(짱)
http://theopentutorials.com/tutorials/eclipse/dtp/eclipse-dtp-configure-h2-datasource-using-data-source-explorer/

Eclipse DTP: Configure H2 Datasource using Data Source Explorer » the O...
theopentutorials.com

flyway 적용 
gradle flywayMigrate -i
