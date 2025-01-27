# Run-Time-Polymorphism

package main1;
class Dress{
    public void wear() {
        System.out.println("The Kurti is so Beautiful...!");
    }
}

class Pink extends Dress {
    public void wear() {
        System.out.println("The Kurti Color Is PINK..");
    }
}
class Lavender extends Dress {
    public void wear() {
        System.out.println("The kurti Color is Lavender...");
    }
}
public class Main1{
    public static void main(String[] args) {
        Dress s1 = new Pink();
        Dress s2 = new Lavender();
        s1.wear(); 
        s2.wear();
    }
}

Output:
The Kurti Color Is PINK..
The kurti Color is Lavender…
