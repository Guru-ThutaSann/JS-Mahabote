# JS-Mahabote
 Here is an explanation of how to calculate the Mahabote, which is an ancient astrology system of the Burmese people. The current version is 1.0.0, and I will update it again later.

# The following features can be used in Mahabote v1.0.0:

(1) Calculation of Julian Date<br>
(2) Calculation of Myanmar Year<br>
(3) Calculation of Mahabote Modulo<br>
(4) Getting Weekday Number<br>
(5) Getting Weekday Myanmar Name<br>
(6) Getting Mahabote House Name<br>

# How to use:
Clone the repository <br>
Double and open index.html

# Usage:
````javascript
const mahabote = new Mahabote(2024, 1, 18, 12, 30, 0);

//Julian Date
const julianDate = mahabote.calcJD();
console.log(`Julian Date: ${julianDate}`);

//Myanmar Year
const myanmarYear = mahabote.get_mmYear();
console.log(`Myanmar Year: ${myanmarYear}`);

//Mahabote House
const zodiacHouse = mahabote.getHouse();
console.log(`Mahabote House: ${zodiacHouse}`);

//Mahabote Modulo
const modulo = mahabote.getModulo();
console.log(`Mahabote Modulo: ${modulo}`);

//Weekday Number
const weekdayNumber = mahabote.getDayNumber();
console.log(`Weekday Number: ${weekdayNumber}`);

//Weekday Myanmar Name
const weekdayName = mahabote.getDayString();
console.log(`Weekday Myanmar Name: ${weekdayName}`);
````
