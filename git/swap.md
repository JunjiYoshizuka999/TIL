//一時変数を使った変数の入れ替え

import java.util.*;
public class Main {
    public static void main(String[] args) {
        // 自分の得意な言語で
        // Let's チャレンジ！！
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        int y = sc.nextInt();
        
        int a = x;
        x = y;
        y = a;
        
        System.out.println(x + " " + y);
    }
}
