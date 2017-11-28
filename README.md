# HCardACS

# T1Final: PartOne a : submit cemetery pseudocode [here](https://docs.google.com/forms/d/e/1FAIpQLSe6wxuURu7cEZbnauaMqay3gYjyQlzNqhznjdRAcevFdL_BwA/viewform)

## With your cemetery group, write a Person class that implements the [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html?is-external=true) interface.  The compareTo() method should sort by burial date, then name.  The class should have first name, last name, burial date and address as instance variables.  The class should have more than one constructor that takes in data in different ways.  In addition, the class should have getters and setters as needed.  The toString should print the data by first name, last name, burial date. 

## You may need to examine the data [here](https://github.com/ACS-Curriculum/Lab3.StringsRegEx/blob/master/1.stringsLabs!/cemetery.txt ).  RegEx will help parse the data [here](http://www.rexegg.com/regex-quickstart.html#quantifiers) and [here.](https://regexr.com/)

## If you are feeling adventurous, build a class that implements the [Comparator](https://docs.oracle.com/javase/8/docs/api/java/util/Comparator.html) interface. The Comparator interface has a compare(T o1, T o2) method that takes two parameters of the data type (T) you are comparing. In the case below, the College objects are being compared using the getAverage() method.   Put your code into a github gist, copy the link and paste it [here.](https://docs.google.com/forms/d/e/1FAIpQLSfgjoBvnGERIXw2oMoP0K8KRl-2pNdITE5_Xizijf9Vm-dqBQ/viewform)  Once completed, move to part b below.



```java
import java.util.Comparator;
class CollegeComparator implements Comparator<College> {

  @Override
    int compare(College c1, College c2) {
    if (c1.getAverage()>c2.getAverage()) {
      return 1;
    } else if (c1.getAverage()<c2.getAverage()) {
      return -1;
    }
    return 0;
  }
}
```


# T1Final: PartOne b
- [HolidayCardHackathon!](https://docs.google.com/document/d/1AEn2_NZ6GxRysGNe7fj2URU4gznswjU4-NPA3dIqFag/edit?usp=sharing)
