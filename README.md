import java.util.*;
public class Stringreverse{
    public static void main(String[] args) {
String s="goods for Geeks";
char[] ch=s.toCharArray();
int left=0,right=ch.length-1;
char temp='0';
for(left=0;left<right;left++,right--){
  temp=ch[left];
  ch[left]=ch[right];
  ch[right]=temp;
    }
    for(char c:ch){
      System.out.print(c);
    }
    }
}
