# CRUD mini Project
-----

## <환자 관리 CRUD project 설계서>

-----

### 활용 방안

#### 환자들의 정보들을 통해서 병원에서는 쉽게 환자들을 관리할 수 있습니다.

특정 환자에게서 어떠한 문제가 일어났을때, 공통점을 가진 환자들을 쉽게 찾아내어 문제가 없는지 등 상황을 빠르게 파악 할 수 있습니다.
##### Example 
특정 질병 A가 환자 (가),(나),(다),(라) 중 (나)를 제외한 모두에게 발병했을때.
검색 기능을 사용하여 A질병을 가진 환자를 검색하여 해당 환자의 정보만 받아옴.
이때, 발병된 환자들이 모두 50~70대라는 공톰점을 발견.

키,나이,몸무게,혈액형,성별이 질병등이 잘 정리되어 빠르게 파악 할 수 있는 환자의 자료를 만들어 낼 수 있습니다.
##### Example
환자들의 진료 기록을 다른 병원에게 전해줘야할때.
저장 기능을 통해 현재 환자의 키,나이,몸무게,혈액형,성별,질병의 정보를 담아서 자료를 만들어 낼 수 있습니다.


환자들의 자료를 받아와서 분류 밑 정렬을 쉽게 할 수 있습니다.
##### Example
불러오기 기능을 통해 다른 병원 환자들의 자료를 받아옴.
다른 병원에서 환자 정보를 받아왔지만, 그 순서가 아무렇게 되어있어 파악하기 힘듬.
정렬기능을 사용하여 환자의 정보를 나이,호관 순으로 정렬하여 정보를 더 쉽게 파악.

-----
-----
-----

#### 다음과 같은 기능들을 가지고 있습니다.
1. 환자 정보 생성 
2. 특정 환자 정보 읽기 
3. 환자 정보 수정 
4. 환자 정보 제거 
5. 환자 리스트 출력 
6. 특정 환자 찾기 
7. 환자 정보 정렬 
8. BMI검사 
9. 파일 읽어오기 
10. 파일저장하기 
0. 프로그램 종료

##### 1. 환자 정보 생성 (create)

환자의 정보를 만든다.
  정보들(이름 / 나이 / 키 / 몸무게 / 혈액형 / 성별 / 질병 / 호관)을 기입한다

##### 2. 특정 환자 정보 읽기 (Read)

원하는 환자의 이름을 입력받아. 
  정보들(이름 / 나이 / 키 / 몸무게 / 혈액형 / 성별 / 질병 / 호관) 을 출력한다.

##### 3. 환자 정보 수정 (Update)

  원하는 환자의 이름을 입력받아. 정보(키 / 몸무게 / 호실)를 수정한다.

##### 4. 환자 정보 제거 (Delete)

  원하는 환자의 이름을 입력받아. 정보들을 삭제한다.

##### 5. 환자 리스트 출력 (List)

  병원내 존재하는 모든 환자들의 정보를 출력한다. 이때, 정보는 정보를 입력받은 순으로 정렬된다.

##### 6.특정 환자 찾기 (Search)

  환자의 정보중에서 특정한 조건(나이, 혈액형, 성별, 질병, 호관) 을 가진 환자의 정보만 출력한다.

##### 7.환자 정보 정렬 (Sort)

  환자들의 정보를 특정한 조건 (나이 , 호관)에 맞춰 정렬한다.

##### 8.BMI검사 (BMI_TEST)

  저장된 환자들의 키와 몸무게의 정보를 통해 BMI (몸무게 / (키 * 키))값과 환자의 비만 여부를 출력한다.

##### 9.파일 읽어오기 (Load)

  프로그램 외부에 정보가 저장되어있다면 Load를 통해 프로그램 밖의 파일 정보를 불러올 수 있다. 불러 올 정보의 파일 이름을 입력한다.

##### 10. 파일저장하기 (Save)

  프로그램 내부에 정보가 저장되어있다면 Save를 통해 현재 정보를 저장할 수 있다. 저장 할 정보의 파일 이름을 입력한다.

##### 0. 프로그램 종료 (Quit)
  
  프로그램을 종료합니다. 이때 정보가 저장되진 않으니 정보를 저장하고싶다면 Save를 통해 파일의 형태로 저장후 종료해야 합니다.
  
-----
-----

  
#### 제작자: 김강훈
