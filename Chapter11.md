## Chapter 11
1. 시스템 제작과 사용을 분리
    1. main 분리
        1. 제작: main
        2. 사용: 그 외
        3. main에서 제작 후 application으로 넘김
        4. 의존성: main → application
2. 팩토리
    1. 추상 팩토리 패턴
        1. 팩토리 메서드 패턴: 조건에 따른 객체 생성을 팩토리 클래스로 위임하여, 팩토리 클래스에서 객체 생성
        2. 추상 팩토리 패턴: 서로 관련이 있는 객체들을 통째로 묶어서 팩토리 클래스로 만듬
    2. [https://victorydntmd.tistory.com/300](https://victorydntmd.tistory.com/300)
3. 의존성 주입
    1. 직접 인스턴스를 만드는 것이 아니라 전담 객체에게 객체를 만들어 줄 것을 요청
    2. 주입 방법
        1. 생성자
        2. 설정자 메서드
4. 확장
    1. 횡단 관심사
        1. 이론적으로는 독립된 형태로 구분될 수 있지만 실제에서는 코드에 산재하기 쉬운 부분들을 뜻한다.
        2. 스프링 AOP
            1. 횡단 관심사의 기능을 모듈화하여 중복을 최소화하면서 핵심 관심사항에 집중하도록 하는 프로그래밍 기법
    2. 자바 프록시
        1. [https://velog.io/@adduci/자바의-동적-프록시](https://velog.io/@adduci/%EC%9E%90%EB%B0%94%EC%9D%98-%EB%8F%99%EC%A0%81-%ED%94%84%EB%A1%9D%EC%8B%9C)
    3. 스프링 AOP 프레임워크
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/73e712db-270a-4c62-a70c-f6c64485fe23/Untitled.png)
        
    4. AspectJ
        1. aop 구현 라이브러리
