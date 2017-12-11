# Lecture 33 - Final Exam Review Session 1

1. Pretend you are developing a car racing video game. To this end, you have already created a Car class. Write a short segment of Java code which creates an array list of NUM_RACERS cars. Assume the Car constructor takes no parameters.
1. Based on the previous exercise, write a short segment of Java code which tells each car object to start its engine. Assume the Car class includes the following method:

        public void startEngine()

1. Simplify the following Java code segment as fully as possible while preserving its behaviour:

        while (x <= 13)
        {
            if (x < 0)
        {
            y = y – 1;
            System.out.println("Petra");
            x = scanner.nextInt();
        }
            else if (x >= 0 && x <= 20)
        {
            y -= 1;
            System.out.println("Valentine");
            x = scanner.nextInt();
        }
            else
        {
            System.out.println("Bonzo");
        }

        }
        if (x > 3)
        {
            System.out.println("Ender");
        }
        else
        {
            System.out.println("Bean");
        }

1. Write a segment of Java code which prints the following output to the terminal window:

        17 16 15 14 13 12 11
        27 26 25 24 23 22 21
        37 36 35 34 33 32 31
        47 46 45 44 43 42 41
        57 56 55 54 53 52 51
        67 66 65 64 63 62 61
        77 76 75 74 73 72 71
        87 86 85 84 83 82 81
        97 96 95 94 93 92 91

    Attempt to minimize code duplication and the amount of code written.

1. In Java, what is the purpose of a constructor? In what way(s) do constructors differ from other methods?
1. Define a Java class named `DigitalWatch` which encapsulates a time in “hh:mm” format, where the hour is between 0 and 23, and the minute is between 0 and 59. Provide it with a constructor, an incrementMinute method and a toString method.
1. In class, you instructor said that the `new` operator performs certain tasks. What are they, in order?
1. Consider the following class definition:

        public class Thing {
            private int i = 0;
        
            public Thing(int j) {
                i = j;
            }
        
            public void inc() {
                i++;
            }
        }

    Trace the following. As you trace, maintain a picture of memory and a picture of the terminal output.

        someMethod() {
            Thing x;
            Thing y = new Thing(10);
            new Thing(20).inc();
            x = new Thing(9);
            Thing z = y;
            x.inc();
            y = null;
            if (z == x) {
                System.out.println("same");
            }
            else {
                System.out.println("diff");
            }
        }
1. "The use of FileNotFoundException tends to 'spread' throughout your code." What is meant by this? Did you see this happen in assignment 8? In what way? 
1. Give an example of each of the following common programming gotchas:
    1. off by one error
    1. comparing Strings with ==
    1. forgetting how integer division
    1. accidentally creating an infinite loop
    1. dividing by 0
    1. using a local variable when you think you're using an instance variable
    1. forgetting to instantiate classes before using them
1. Design a class that can represent the weather observed on a given day. Assume you need to track the high and low temperatures on that day, as well as the amount of precipitation in mm. Your class should have accessors and mutators for each field, a reasonable constructor, and a toString.
    1. Write a statement illustrating how you could create an instance of your class.
1. Create a method that is given the name of a file and then reads the file word-by-word and returns the average word length of all words in that file. You can assume all words are separated by white space - no need to worry about punctuation and the like. If the file is empty, your method should return 0. Don't use an ArrayList. Include any and all imports required to make your method compile.

        