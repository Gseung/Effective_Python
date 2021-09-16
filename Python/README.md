### Chapter 1. 파이썬답게 생각하기
Better way 1. 사용 중인 파이썬의 버전을 알아두라   
Better way 2. PEP 8 스타일 가이드를 따르라   
Better way 3. bytes와 str의 차이를 알아두라   
Better way 4. C 스타일 형식 문자열을 str.format과 쓰기보다는 f-문자열을 통한 인터폴레이션을 사용하라   
Better way 5. 복잡한 식을 쓰는 대신 도우미 함수를 작성하라   
Better way 6. 인덱스를 사용하는 대신 대입을 사용해 데이터를 언패킹하라   
Better way 7. range보다는 enumerate를 사용하라   
Better way 8. 여러 이터레이터에 대해 나란히 루프를 수행하려면 zip을 사용하라   
Better way 9. for나 while 루프 뒤에 else 블록을 사용하지 말라   
Better way 10. 대입식을 사용해 반복을 피하라   

### Chapter 2. 리스트와 딕셔너리
Better way 11. 시퀀스를 슬라이싱하는 방법을 익혀라   
Better way 12. 스트라이드와 슬라이스를 한 식에 함께 사용하지 말라   
Better way 13. 슬라이싱보다는 나머지를 모두 잡아내는 언패킹을 사용하라   
Better way 14. 복잡한 기준을 사용해 정렬할 때는 key 파라미터를 사용하라   
Better way 15. 딕셔너리 삽입 순서에 의존할 때는 조심하라   
Better way 16. in을 사용하고 딕셔너리 키가 없을 때 KeyError를 처리하기보다는 get을 사용하라   
Better way 17. 내부 상태에서 원소가 없는 경우를 처리할 때는 setdefault보다 defaultdic를 사용하라   
Better way 18. __missing__을 사용해 키에 따라 다른 디폴트 값을 생성하는 방법을 알아두라   
Better way 19. 함수가 여러 값을 반환하는 경우 절대로 네 값 이상을 언패킹하지 말라   

### Chapter 3. 함수
Better way 19. 함수가 여러 값을 반환하는 경우 절대로 네 값 이상을 언패킹하지 말라   
Better way 20. None을 반환하기보다는 예외를 발생시켜라   
Better way 21. 변수 영역과 클로저의 상호작용 방식을 이해하라   
Better way 22. 변수 위치 인자를 사용해 시각적인 잡음을 줄여라   
Better way 23. 키워드 인자로 선택적인 기능을 제공하라   
Better way 24. None과 독스트링을 사용해 동적인 디폴트인자를 지정하라   
Better way 25. 위치로만 인자를 지정하게 하거나 키워드로만 인자를 지정하게 해서 함수 호출을 명확하게 만들라   
Better way 26. functools.wrap을 사용해 함수 데코레이터를 정의하라   

