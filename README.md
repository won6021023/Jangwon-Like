# Jangwon-Like-Unity-Homework(이장원)
내일배움캠프 - Unity 게임개발 심화 개인과제

## 구현 내용

### 플레이어
- InputSystem 구축
        - WASD : 이동
        - Left Click : 공격
        - Mouse Scroll : 카메라 확대/축소

### 맵
- 타일 맵을 이용해 맵을 만들었습니다.
- Tilemap Collider를 통해 캐릭터가 벽을 통과하지 못합니다.

### 카메라
- 캐릭터 따라 메인 카메라가 움직입니다.

### 몬스터
    - 애니메이터 : Override Controller 활용
    - 피격시 시각 효과
    - 스크립터블 오브젝트로 상수 관리
    - 몬스터 패턴별 분리 구현 : Follower, Straight

### 게임 시스템
    - 몬스터 레벨 디자인
    - 무작위 몬스터 출현 이벤트 구축
    - 오브젝트 간 충돌 이벤트 및 시각 효과 구현

### 오브젝트
    - 투사체
       - 요소 디자인 및 프리팹화

    - 트랩 오브젝트 추가

    - 아이템
       - 요소 디자인 및 프리팹화
       - 아이템 드롭 컨트롤러 구축

    - 무기
       - 랜덤 무기 획득 시스템
   
    - 투사체
       - 같은 무기 획득 시 투사체 증가

