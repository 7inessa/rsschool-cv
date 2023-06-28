**#Brovkova Inna**
***
Junior Frontend Developer
===
![Inna](Путь к файлу "Подпись")
+++
Contact information:
Phone: +7 707 627606
E-mail:  inna.ignashkova@gmail.com
Telegram: @inessa
***
Briefly About Myself:
Remote work as a retoucher gives me extra free time, which I spend learning Frontend Development.
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.
***
#Skills and Proficiency:
*HTML5, CSS3
*JavaScript Basics
*Git, GitHub
*VS Code, IntelliJ IDEA
*Adobe Photoshop, Illustrator

#Code example:
Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.
```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
~~
Native Russian
Computer literacy 
