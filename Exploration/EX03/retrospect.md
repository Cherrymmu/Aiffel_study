많은 시도는 해보지 못하였지만, seq_map을 건드리고, 필터를 건드리고, 이미지를 이동해서 다시 세그먼테이션을 하는 행위를 해 보았습니다.
어제 컨디션이 좋지못해 수업을 잘 진행하지 못하였습니다.
오늘 열심히 하였는데, 새로운 모델까지 추가해서 작업하는 것은 시간이 부족했습니다.
대신 필터나, 모폴리지연산? 같은 것들을 사용해 보았는데, 커널사이즈를 다뤄보았는데 세그멘테이션이 넓어지는 현상이 발생하였습니다.
- K
    - 모폴리지 연산을 사용하여 보았다.
- P
    - 털이 삐져나오는 것을 해결하지 못함
    - 클래스별 윤곽선이 생겨버리는 현상 발생
- T
    - 모폴리지 연산을 통해 세그멘테이션의 범위를 늘려봄, 하지만 이러면 정확한 범위및 정확도를 알 수 없을듯
