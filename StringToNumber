public class StringToNumber{
  public static void main(String[] args) {
      System.out.println(stringToNumber("1933943"));;
  }
  public static int stringToNumber(String s){
    int temp=0;
    int n=s.length()-1;
    for(int i=s.length()-1;i>=0;i--){
        char k = s.charAt(i);
        if(k<48 || k>57)
            return 0;
        temp += (k - '0') * Math.pow(10,n-i);
    }
    return temp;
  }
}
