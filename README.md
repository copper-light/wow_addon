# wow_addon
와우 에드온




## HDH_AuraTracking
- 오라,스킬,토템,HP,MP,직업자원에 대한 쿨다운 및 수치를 별도의 아이콘(바)으로 만들어 표시
- -------------------- 업데이트 사항 -------------------- 

동작하지 않는 문제에 대해서 제보 해주시면 감사하겠습니다.

[2018.10.02 21:00] v8.0.1.5
- 운무 마나바 추가
- 액션바와 충돌되던 문제 수정

[2018.07.23 23:50] v8.0.1.4
- 흑마법사의 영혼의조각 자원이 제대로 동작하지 않는 문제 수정

[2018.07.23 23:50] v8.0.1.3
- 모든 주문 추적에서 아이콘 이미지가 보이지 않는 문제 수정
- 죽음의기사 직업에서 애드온이 동작하지 않는 문제 수정

[2018.07.22 19:02] v8.0.1.2
- 도적 연계 포인트가 제대로 표시되지 않는 문제 수정
- 자원 추적이 제대로 작동하지 않는 문제 수정
- 주문 추적이 제대로 작동하지 않는 문제 수정
- 툴팁에 주문 ID가 제대로 표지 되지 않는 문제 수정
- 주문 수치가 제대로 표시 되지 않는 문제 수정
- 채팅창에 로그가 출력되던 문제 수정


source: imgur.com

------------------- 애드온 설명 --------------------- 

1. 오라 추적
사용자가 지정한 오라(버프, 디버프)가
[ 비활성화 ] 되었을 때는 [ 흑백 아이콘 ] 으로, 
[ 활성화 ] 되었을 때는 [ 컬러 아이콘(+쿨다운,중첩) ] 으로 표시가 가능한 애드온입니다.

2. 스킬 쿨타임 추적 

3. 토템류 스킬 추적(꽃피우기, 마력룬, 조각상)

4. 직업 별 자원 추적 
- 마나, 기력, 소용돌이, 광기, 룬마력
- 죽기 룬, 콤보, 비전충전몰, 영혼조각 등 모든 자원 추적 가능이 가능합니다.
source: imgur.com

5. 양조 시간차 추적
source: imgur.com

6. 오라의 각종 수치 표시
- 화법 작열, 흑마 불안정한 고통, 복술 폭우토템, 보호막류의 수치 표시
(백만 단위는 'm' 으로, 천 단위는 'k' 로 축약 되어 표시됩니다)

예2) 화염 마법사의 작열 도트 데미지 표시
source: imgur.com
- 작열ID : 12654



--------------------- 안내 사항 --------------------- 

※ 설정창 팝업 명령어는 /at , /auratracking , /ㅁㅅ 입니다.

※ 주문, 아이템의 ID을 알고 싶은데, 게임 내에서 직접 확인하는거 외에 다른 방법 없을까요?
- 와우레이더 사이트 검색창에 주문,아이템 명을 검색해보면, 웹브라우저 주소창에 ID 가 있습니다.
- http://wowraider.net/news/ko/
source: imgur.com


-------------- 알려진 오류 및 대처방법 ----------------- 

- 오류: 쿨다운 시간 2개가 겹쳐서 나오는 문제 
원인: "쿨다운 시간 표시 애드온(ex:tdCooldown)"을 사용하는 경우, 쿨다운 방향을 원형으로 했을때 발생.
해결: 쿨다운 방향을 원형 외에 다른 것으로 설정하거나, 쿨다운 숫자 표시 설정을 표시 안함으로 설정

※ 와우 내장 사운드 파일의 경로를 찾고자 하신다면, 
http://www.wowinterface.com/downloads/info13194-SoundcommandsforeverysoundupdatedforMoP.html
에서 찾으시길 권장합니다.

※ 일부 문제가 발생 된다면 설정에서 Aura, UI 초기화를 해주세요.

## HDH_UnitFrame
- 와우 기본 유닛프레임에서 HP, MP 의 크기를 변경한 유닛프레임

## HDH_ActionBar_Range
- 스킬 유효거리에 따른 액션바의 스킬 아이콘 빨갛게 표시
