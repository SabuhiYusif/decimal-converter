public class DecimalConverter{
    public static void main(String[] args){
    
        long N = Long.parseLong(args[0]);  // Decimal Number
        int  k = Integer.parseInt(args[1]); // Converted base
    
        String s = "";
     
        for (long n = N; n > 0; n /= k){
          if(n % k == 10){
             s =  "A" +s;
          }else if(n % k == 11){
             s = "B"+s;
          }else if(n % k == 12){
             s = "C"+s;
          }else if(n % k == 13){
             s = "D"+s;
          }else if(n % k == 14){
             s = "E"+s;
          }else if(n % k == 15){
             s ="F"+s;
          }else{
             s = (n % k) + s;
          }

         }
        System.out.println(s);
  }
    
}
