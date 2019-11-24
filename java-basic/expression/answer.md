# Bài 1 (a = 10, b = 15). 
- `5 + 7 / 2 + 20 --> 28`
- `5 > 6 || 6 > 5 && 3 >= 2 --> true`
- `!(3 * 5 == 1 * 6) --> true`
- `20.2 / 2 + 7 --> 17.1`
- `b / (double) a --> 1.5`
- `a <= 10 && a + 5 <= b --> true`
- `28 / (int) Math.pow(1 + 2, 2) --> 3`
- `b % 4 + "xau" --> 3 xau`

# Bài 2. 
```java int a;
a = 2 >= 2 ? 2 : 3;
a ++;
a = a + 3;
a *= 5 / 2;```

--> Kết quả: 
`a = 12`

# Bài 3 
    '''java public static void main(String[] args) {
        double diemMieng, diem15Phut, diem1Tiet, diemThi, diemTrungbinh;
        diemMieng = 8.5;
        diem15Phut = 9.0;
        diem1Tiet = 8.5;
        diemThi = 8.0;
        diemTrungbinh = (diemMieng + diem15Phut + diem1Tiet * 2 + diemThi * 3) / 7;
        System.out.println(diemTrungbinh);``` 
# Bài 4
    '''java public static void main(String[] args) {
        int a = 5, b = 9;
        System. out. println(a >= b ? a : b);
        }'''
# Bài 5
    ```java public static void main(String[] args) {
        int a = 5, b = 9, c = 10;
        System. out. println(a >= b && b >= c ? a : (b >= a && b >= c ? b : c));
        }```
