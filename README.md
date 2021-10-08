## oracle
***

### 패키지

연관성이 있는 함수나 프로시저를 그룹으로 모아놓은 개념

변수, 상속, 서브프로그램들의 항목을 묶어놓음

여러가지 항목들을 모아 하나의 이름으로 묶어놓은 객체

패키지는 컴파일 과정을 거쳐 데이터베이스에 저장되며 다른 프로그램에서 패키지의 항목을 참조하고 실행할 수 있다.

 * 모듈화 기능

     업무적으로 연관성이 있거나 비슷한 기능을 수행하는 서브 프로그램등을 하나의 패키지에 담아두면 이해 및 관리하기 쉽다
     
 * 프로그램 설계의 용이

    패키지는 선언부(스펙)과 본문(바디)로 구성되는데, 선언부만 있어도 컴파일한 뒤에 저장이 가능하다.
    
    
 * 캡슐화

    선언부는 외부에 공개되지만, 패키지에 속한 커서, 함수, 프로시저의 세부 구현내용이 담겨있는 본문은 외부에서 볼 수 없다.
    즉, 정보 은닉 기능이 지원되는 것이며, 외부 모듈에 영향을 주지 않고도 패키지 본문 내용은 언제든지 수정할 수 있다.
    
* 보다 나은 성능

    패키지에 있는 서브 프로그램을 호출하면 일단 해당 패키지 전체를 메모리에 올려놓는데, 이후 계속 호출하더라도 메모리에 올라가있는 상태이므로 더 나은 성능을 보인다.
 
 
 ### Procedure
 
    특정 작업을 수행 하는, 이름이 있는 QL/SQL BLOCK 이다.
    
    매개 변수를 받을 수 있고, 반복적으로 사용 할 수 있는 BLOCk이다.
    
    보통 연속 실행 또는 구현이 복잡한 트랜잭션을 수행하는 PL/SQL BLOCK을 데이터베이스에 저장하기 위해 생성 한다.
    
    
 
    
      
