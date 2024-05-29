# 지도 부분



## :satellite: 주소 데이터 수집


- 시장명 데이터를 수집해 엑셀 파일로 데이터를 정리


- **시장 정리.xlsx에 전체 정보 저장, 각 도 별로는 Market_data에 정리**


- 주소 데이터를 가지고 위도, 경도로 변환하는 작업 진행. 지도는 카카오맵 사용


- **변환 작업 중 주소가 맞지 않거나 위치에 오류가 있는 경우 일일이 수정 후 저장**


- [주소-> 위도경도 변환 사이트](https://deveapp.com/map.php) 사용해 위도,경도 정보 수집



## :clipboard: 지도 api 이용해 정보 표기


- [카카오맵 api](https://apis.map.kakao.com/) 를 이용해서 시장 정보를 지도상에 표시하는 작업 진행


- Android, Web, iOS 중 Web 사용



## :pushpin: Market_Map_Pin


- 위도경도로 변환한 데이터를 토대로 시장 위치를 지도상에 표시


- 이 작업에서는 간단히 시장의 위치만 지도상에 핀으로 나타냄




## :fork_and_knife: Map_Visualization


- 웹과 직접적으로 연동되는 지도 부분이다.


- 위도경도를 바로 지정해 시장의 위치가 바로 뜨며, 시장의 이름, 주소, 전화번호, 홈페이지의 정보가 나타난다.


- 홈페이지가 있는 시장도 있고 없는 시장도 있는데, 있을 경우 시장 홈페이지로 바로 이동할 수 있도록 하였다.





### 끝

***api를 연동하는 코드는 api문제로 인해 삭제하고 재업로드함***



