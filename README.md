# Vi_Earth

VI Earth의 11주차 프로젝트 진행 사항

![KakaoTalk_20201117_001527080_02](https://user-images.githubusercontent.com/54584364/99271224-2d80eb00-286a-11eb-868d-b5f88ead8057.jpg)

![KakaoTalk_20201117_001527080_03](https://user-images.githubusercontent.com/54584364/99271446-3d003400-286a-11eb-9cfc-9a72bfb3b15c.jpg)

[실행 영상](https://youtu.be/r1GyV1tAzdM)

![KakaoTalk_20201117_001527080](https://user-images.githubusercontent.com/54584364/99271619-48ebf600-286a-11eb-948c-d7aaf82650a2.jpg)

[실행 영상](https://youtu.be/QUyOxa9Z-UU)

![KakaoTalk_20201117_001527080_01](https://user-images.githubusercontent.com/54584364/99271773-57d2a880-286a-11eb-91fb-68b437bc0a4b.jpg)

[실행 영상](https://youtu.be/ycVoJ6Xu7p4)

1. 전체적인 맵 재구성
- 

2. 맵을 기반으로 미니맵 재구성
- 

3. 미션에 해당하는 미니게임 구성

3-1. 서점 미션 미니게임
- 사용자가 책 오브젝트에 다가가서 상호작용 버튼을 누르면 책 이미지가 보여지고 주어진 조건의 페이지를 펼치면 미션이 완료됩니다.
- 해당 미션은 Asset Store에 무료로 업로드되어 있는 "Book - Page Curl"을 활용하였으며 해당 오픈코드의 출처는 명확히 제시하겠습니다.
- 해당 미션은 아직 책 넘기는 기능만을 담고있어 미션 오브젝트와 연결하지 못하였고 랜덤 페이지 수 조건을 생성하여 미션이 완료되는 진행은 아직 구현하지 못했습니다.

3-2. 발전소 미션 미니게임
- 사용자가 발전기 오브젝트에 다가가서 상호작용 버튼을 누르면 전체적인 발전소 이미지가 보여지고 발전기 앞에 손잡이를 돌리면 주변에 8개의 빛이 차례대로 생성되며 8개의 빛이 모두 생성되면 미션이 완료됩니다.
- 해당 미션은 사용자가 터치를 할때 초기 좌표값을 저장하고 그 이후 변화된 좌표값의 차이를 구하여 터치의 벡터값을 구하고 해당 벡터로 기준점으로부터의 각도로 변환하여 손잡이 오브젝트를 rotation시켰습니다.
- 해당 미션은 아직 미션오브젝트와 연결하지 못하였고 한바퀴 돌때마다 하나의 빛이 보여줘야하는데 이부분이 아직 보완되지 않았습니다. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
