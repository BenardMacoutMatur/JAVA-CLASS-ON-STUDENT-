/*Create a class student and a function to get the student details*/
public class Student{
    public String name;
    public int age;
    public String course;
    public String university_name;
// create a function that will dispay the details of the user.

}

public class Main{
    public static void main(String[]args){
        // create an object to access the code of this.
        // class object name= new class
        Student s1 = new Student();
        s1.name ="Macout Matur";
        s1.age = 22;
        s1.course = "Data Science and Analytics";
        s1.university_name ="Jommo Kenyatta University Of Kenya";

        System.out.println("Your name is "+s1.name);
        System.out.println("Your age is "+s1.age);
        System.out.println("Your course is "+s1.course);
        System.out.println("Your university name is "+s1.university_name);
    }
}
