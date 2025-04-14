# charatforJY
// This code takes a string input from the user and prints each character of the string on a new line. It reads the entire string, then iterates through each character one by one, displaying them separately for better readability or further processing 

class charatforJY 
{
    public static void main(String[] args) {
        String city;
        city = new String("bhopal");
        int n;
        System.out.println(city);
        n=city.length();    
      for(int i=0;i<n;i++)
      {

        char digit;
        digit=city.charAt(i);
        System.out.println(digit);
      }

       
        }
}
