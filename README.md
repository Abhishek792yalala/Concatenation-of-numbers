# Concatenation-of-numbers



class Code {
        public int m1(int a, int b) {
            System.out.println("concatenation of a and b is: " + a + b);
            return a + b;
        }

        public int m1(int c, int d, int f) {
            System.out.println("concatenation of c,d and f is: " + c + d + f);
            return c + d + f;
        }


        public static void main(String... args) {
            System.out.println("Welcome to java programming");
            Code cc = new Code();
            cc.m1(1, 2);
            cc.m1(1, 2, 3);

        }

}
/*
Welcome to java programming
concatenation of a and b is: 12
concatenation of c,d and f is: 123
 */



