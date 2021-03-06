### Dat19b - Programmering 2 - 3. Semester Forår 2020
Underviser: Claus Bove, clbo@kea.dk


| Uge | Dato | Emne | 
| --- | --- |
||| [Introduktion til Programering 2](w35_intro.md) | 
||| [OOP recap: Encapsulation, Abstraction, Inheritance & Polymorphism](w36_recap_oop.md)|
||| [Recap: ADT: Lists, Sets, Interface, Generics ](w36_Recap_ADT_Lists_Sets_Maps_Interface_Generics.md)| 
||| [Recap: Spring Boot MVC](w37_recap_mvc_I.md) |  
||| [Recap: Spring Boot MVC](w37_recap_mvc_II.md)|
||| [Spring Testing Frameworks (Unit Tests)](w38_unittest_I.md)	|
||| [Feedback, Q&A](w38_unittest_II.md)	|
||| [Spring Testing Frameworks (Mockito & Spring MVC)](w39_unittest_III.md)	|
||| [Javascript](w39_javascript.md)	|
||| [Jquery & Ajax I](w40_ajax_jquery.md)	|
||| [Spring Boot JPA I](w40_spring_jpa.md)	|
||| [Spring Boot JPA II](w40_spring_jpa.md)	| 
||| [Spring Boot JPA III](w40_spring_jpa.md)	|
||| [**Obligatorisk opgave (online) (8:45 - 15:30)**](w42_obligatorisk_opgave.md)	|
||| Ingen undervisning |
||| [Spring Boot REST I](w43_rest.md)	| 
||| [Spring Boot REST II](w43_rest.md)	|
|||  |
|||  |
||| [Design Patterns (Low coupling, MVC, Observer, Repository)](w45_design_patterns.md)	|
||| [Design Patterns (Low coupling, MVC, Observer, Repository)](w45_design_patterns.md)|
||| [Design Patterns (MVC, Composite, Strategy)](w46_design_patterns_strategy.md)	|
||| [Design Patters (Decorator)](w46_design_patterns_decorator.md)	|
||| [Spring Boot Chat Server Application](w45_Spring_Boot_Chat_Server_Application.md)	|
||| [Spring Boot Chat Server Application I](w45_Spring_Boot_Chat_Server_Application.md)	|
||| [Nodejs websockets & Docker](w48_websockets_node.md)	|
||| [Nodejs websockets & Docker](w48_websockets_node.md)	|
||| [Recap & Eksamensforberedelse](w49_recap_1.md) 	|
||| [Recap & Eksamensforberedelse]() 	|
||| [Recap & Eksamensforberedelse]() 	|
||| [Recap & Eksamensforberedelse]() 	|



<script>  

var dates = [
	{week:35, date: '28/8'},
	{week:36, date:	'3/9' },
	{week: '' ,  date:	'4/9' },
	{week:37, date:	'10/9' },
	{week: ''	, date:'11/9' 	},
	{week:38, date:	'17/9' 	},
	{week: '' , date:	'18/9' 	 },
	{week:39, date:	'24/9' 	 },
	{week: '' ,date:	'25/9' 	 },
	{week:40, date:	'1/10' 	 },
	{week: '' , date:	'2/10' 	 },
	{week:41, date:	'8/10' 	 },
	{week: '' , date:	'9/10' 	 },
	{week:42, date:	'15/10' 	 },
	{week:'' , date:	'16/10' 	 },
	{week:43, date:	'22/10' 	 },
	{week:'' , date:	'23/10' 	 },
	{week:44, date:	'29/10' 	 },
	{week:''  ,date:	'30/11' 	 },
	{week:45, date:	'5/11' 	 },
	{week:''  ,date:	'6/11' 	 },
	{week:46, date:	'12/11' 	 },
	{week:''  ,date:	'13/11' 	 },
	{week:47, date:	'19/11' 	 },
	{week:'' , date:	'20/11' 	 },
	{week:48, date:	'26/11' 	 },
	{week:''  ,date:	'27/11' 	 },
	{week:49, date:	'3/12' 	 },
	{week:''  ,date:	'4/12' 	 },
	{week:50, date:	'10/12' 	 },
	{week:''  ,date:	'11/12' 	 },
	{week:51, date:	'17/12' 	 }

]
var table = document.getElementsByTagName("table");  
var tbody = document.getElementsByTagName("tbody")
var rows = document.getElementsByTagName("tr");  
for(i = 1; i < rows.length; i++){  
  var tds = rows[i].getElementsByTagName("td"); 
  tds[0].innerHTML= dates[i-1].week;
  tds[1].innerHTML= dates[i-1].date;
}
</script>
