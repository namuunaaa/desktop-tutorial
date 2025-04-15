Nomad Livestock Simulation
OOP зарчмуудыг ашиглан Монголын нүүдэлчин айлын мал аж ахуйн менежментийн Java загварчлал.

Object oriented programming - lab 4-3
B241910014 Namuunaa.B

Features
Abstract Class (Livestock): Base class for all animals.
Interface (WorkRole): Defines specific tasks for working animals.
Classes (Horse, Sheep, Camel, Goat): Implement different animal behaviors.
Polymorphism: Manages diverse animals uniformly.
Herd Class: Simulates daily routines.
Code Structure
Livestock (Abstract Class):
Defines name, age, makeSound(), and graze().
WorkRole (Interface):
Defines performTask().
Animal Classes (Horse, Sheep, Camel, Goat):
Extend Livestock, implement WorkRole (if applicable).
Override makeSound() and performTask().
Herd Class:
Manages ArrayList<Livestock>.
Implements addLivestock() and dailyRoutine().
How to Run
Clone the repo.
Open in a Java IDE.
Run NomadLivestockDemo.java.
Key Concepts
Abstraction, Inheritance, Interfaces
Polymorphism
Method Overriding & Overloading
Example Output
Баян: Янцгаана!
Морь талбайд уналгад хэрэглэгдэнэ.
Баян талбайд бэлчинэ.
Чулуун: Маа!
Чулуун талбайд бэлчинэ.
Тэмүр: Буйлна!
Тэмээ говийн тээвэрт хэрэглэгдэнэ.
Тэмүр талбайд бэлчинэ.
Сүхбаатар: Мээ!
Ямаа уулын замд ачаа тээвэрлэнэ.
Сүхбаатар талбайд бэлчинэ.
