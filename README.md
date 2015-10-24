# JAVAProgramming1
JAVA OOPs Concepts Example codes
public class StaticBlocks {
    //1.)public void main(String[] args)   //W/O static rises exception no main class found
    //2.)First Static blocks are accessed then main class
    
    static{
        System.out.println("Hi from static block");
    }
    public static void main1(String[] args) {
    
        System.out.println("Hi from main block");
        
    }
    static{
        System.out.println("Hi from second static block");
    }
}
