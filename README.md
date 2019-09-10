<h1>Assignment 2 <br/>Discrete Mathematics: Student Calendar</h1>



<h3>First thing we did, was to come up with some data:</h3>

```pl

class(a, mo).
class(a, hallur) .
class(b, lars).
class(b, jens).
class(c, ali).
class(d, tom).
class(a, kasper).

class_date(date(2019, 7, 30), a).
class_date(date(2019, 5, 30), b).
class_date(date(2019, 3, 30), c).
class_date(date(2019, 3, 30), d).

room(a).
room(b).
room(c).
room(d).

student(mo).
student(hallur).
student(jens).
student(lars).
student(kasper).
student(ali).
student(tom).

```
<h3>Secondly, we wrote down some ideas for methods, that had the requirement of including facts and rules</h3>

<ul>
  <li>get all information on a student</li>
  <li>does student a go in the same class as student b</li>
  <li>does student a go to class at the same date as student b</li>
  <li>get all students</li>
  <li>get all classes</li>
  <li>get all dates</li>
</ul>

<p>To see the original file, click <a href="/ass2.pl">here</a></p>

<h3>Commands in SWI-Prolog</h3>
<p>Open the file in SWI then run those commands:</p>
<ul>
  <li>getStudentInfo(hallur) .</li>
  <li>sameClass(mo,hallur) .</li>
  <li>sameDate(ali, tom) .</li>
  <li>getAllDates() .</li>
  <li>getAllStudents() .</li>
  <li>getAllClasses() .</li>
</ul>

