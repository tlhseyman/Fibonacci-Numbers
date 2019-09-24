package sample;

public class FibonacciNumbers1 {
    public static void main(String[] args) {
        int m=0;
        int n=1;
        int k;
        int limit=10;
        System.out.print(m + " " + n);
        for(int i=2; i<limit; i++){
            k=m+n;
            System.out.print(" " + k);
            m=n;
            n=k;
        }
    }
}
