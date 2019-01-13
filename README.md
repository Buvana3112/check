//# check
//to check the gn number is positive or negative or zero
class Check{
   public static void main(String args[]){
      Scanner s=new Scanner(System.in);
      int n=s.nextInt();
      if(n>0)
         System.out.println("Positive");
      else if(n<0)
         System.out.println("Negative");
      else
         System.out.println("Zero");
  }
}
         
