type:: [[Class]]
parent:: [[Thing]]
description:: 사용자 정의 클래스/타입을 정의하기 위한 사용자 정의 클래스.
sameas:: [RDF Class](https://www.w3.org/2000/01/rdf-schema#Class)

- # User Defined Class
- 정확히는 사용자 정의 클래스는 `logseq`의 built-in property인 `type`에 사용될 클래스 입니다.
- 사용자 정의 클래스는 하나의 페이지로 정의 합니다.
- 그래프뷰 위에서 유의미한 가치를 갖기 위하여 [[Class]] 페이지는 아래와 같은 공통된 페이지 프로퍼티 세트를 갖습니다.
	- type:: [[Class]]
	  parent:: REPLACE WITH SUPER CLASS
	  description:: REPLACE WITH DSCRIPTION
	  sameas:: REPLACE WITH COMMON DEFINITION URL
	  domainincludes:: REPLACE WITH CLASSES/TYPES
	  rangeincludes:: REPLACE WITH CLASSES/TYPES
	  template:: CLASS-PROP-SET
- 이 공통 프로퍼티 중 type 프로퍼티만 required 입니다. 또한 template 프로퍼티는 템플레이팅을 위한 표시이므로 제외입니다.