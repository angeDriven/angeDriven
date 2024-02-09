<html>
<body>
<h1>javascipt classes</h1>
<p>Creating two car objects from a car class:</p>

<p id="demo'></p>

<script>
class car {
 constructor(name, year) {
 	this.name = name;
    this.year = year;
  }
}
const myCar1 = new  Car("Ford", 2015);
const myCar2 = new  Car("Audi", 2019);

documents.getelementbyid("demo"). InnerHTML =
myCar1.name + " " +mycar2.name;
</script>
