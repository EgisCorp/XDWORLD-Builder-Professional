
# XDWORLD-Builder-Professional

[![EgisLogo](https://user-images.githubusercontent.com/82925313/160987075-ce7eada9-91ca-4b72-beb6-396e142f90a2.png)](http://www.egiskorea.com/)

### Developers - http://www.egiskorea.com/

Issues 란에 활용 중 질의 사항을 기술해 주시면 기술하신 내용을 참고하여 상세하게 답변 드리겠습니다.
답변이 업로드 된 issues는 마지막 답변 이후 14일 동안 추가 문의가 없을 시 Close 됩니다.
이어서 진행 하고자 하시는 경우 해당 Issues를 재 오픈 부탁듭립니다.
데이터 Issues 관련해서는 builder@egiskorea.com로 보내주시면 감사 하겠습니다.

## Relese 
### Windows (v_5.0.4 버전부터 배포를 합니다.)
- [v_5.0.5](https://www.dtwincloud.com/builder/product/v_5.0.5.zip)
- [v_5.0.4_vietnam](https://www.dtwincloud.com/builder/product/v_5.0.4_vietnam.zip)
- - ~~[v_5.0.4](https://www.dtwincloud.com/builder/product/v_5.0.4.zip)~~
- ~~[v_5.0.3]()~~
- ~~[v_5.0.2_vietnam]()~~
- ~~[v_5.0.2]()~~
- ~~[v_5.0.1]()~~
- ~~[v_5.0.0]()~~

## Relese Note

### Version 5.0.5
 * 영상 병렬 처리 
   * 기존 병렬처리 "사용" 기능의 경우 복수개 영상을 동시에 병렬로 가공
     * 개별 영상은 일반 속도로 가공
   * 새로 추가된 병렬처리 "사용(한장씩)" 기능의 경우 한장의 영상에서 여러 지역을 병렬로 가공
     * 입력된 영상이 한장, 복수장 관계없이 순서대로 한장씩 가공하며 한장을 병렬로 가공함.
   * 병렬 처리 진행 상태바 표시 방식 개선
       
### Version 5.0.4
 * UI 개선
     
### Version 5.0.4 (Vietnam)
 * UI 개선
       
### Version 5.0.3
 * 가공 속도 개선
   * Erdas img 포맷 (지형, 영상) 가공 속도 개선

 * 영상 가시화 
   * 영상 가시화 레벨 제한 해제 (기존 가공 후 영상 해상도 제대로 안보였던 오류 처리)

 * 사용자 지도 예외처리
   * 영상, 지형 개별 처리 (ex. 영상만 입력할 경우 지형은 기본 지형으로 설정)
     
### Version 5.0.2 (Vietnam)
 * Version 5.0.2 사용
   * 베트남어 UI    
   * 병렬처리 기능 제외
       
### Version 5.0.2
 * Shape 지원 가공 기능 중 하나인 POI 가공 기능 수정
   * 최소, 최대 레벨 UI 추가
   * 폰트 UI 추가
   * 지형 폴더 UI 추가
       
 * 영상, 지형 가공 기능 보강
   * 영상 투명 색상 2 추가, 투명 색상 1은 우선 적용함.
   * 영상 병렬 처리 UI 추가
   * 영상 품질 조절 UI 추가
   * 영상 색상 품질 밝게 조절
   * 영상, 지형 작업 log 추가, 비정상적인 종료 후에도 이전과 같은 설정으로 재시작하면 비정상 종료 직전까지 했던 작업에 이어서 진행
   * 영상 생성 시작 레벨,종료 레벨 추가     
   
### Version 5.0.1
 * 영상병렬가공 PNG 기능 수정
 * LOD1 포맷 가공 오류 수정
   
### Version 5.0.0
 * LOD1 지형결합, 건물지반 방식 추가
 * 라이센스 관련 기능 추가
 * 타임락 기능 추가
 * 다중영상 가공 기능
 * 포인트 클라우드 색상 표현안되는 문제
 * 포인트 클라우드 가시화 시 가시화 엔진과 빌더 화면 위치가 다른 문제
 * 지하 오브젝트 가시화 기능
