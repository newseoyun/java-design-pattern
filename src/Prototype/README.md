# Prototype Pattern
인스턴스를 복사하여 새로운 인스턴스를 만든다
***
> 자바 내장 API인 Cloneable 을 상속한 *Product* 인터페이스와 그것을 상속받은 *MessageBox*, *UnderlinePen*   
> *Manager*로 제어(clone호출)
***
Product 종류가 너무 많을 때,   
커스텀 많이 된 인스턴스를 또 생성할 필요가 있을 때(클래스로부터 생성이 어려울 때),   
클래스 이름의 속박으로부터 분리하여 재사용성을 높일 때 사용.    
(Product 클래스 이름을 쓰지 않고 사용자 정의 protoName 만들어서 씀) 
