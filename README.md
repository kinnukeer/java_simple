# java_simple
public class Main{
  public static void main(String[] args){
    try{
      int[] myNumbers={1,2,3};
      System.out.println(myNumbers[10]);
    }catch(Exception e){
      System.out.println("something went wrong.");
    }finally{
      System.out.println("the 'try catch'is finished.");
    }
  }
}
