# Bài 1
```java
double weight = 70.0, height = 1.8;
double BMI = weight / Math.pow(height, 2);
if (BMI < 18.5)
    System.out.println("Thiếu cân");
else if (BMI < 25)
    System.out.println("Bình thường");
else if (BMI < 30)
    System.out.println("Thừa cân");
else
    System.out.println("Béo phì");
```

# Bài 2

```java
int year = 1996;
if (year % 400 == 0)
    System.out.println(year + " là năm nhuận");
else if (!(year % 100 == 0) && year % 4 == 0)
    System.out.println(year + " là năm nhuận");
else
    System.out.println(year + " không phải là năm nhuận");
```

# Bài 3
```java
char letter = 'e';
switch (letter) {
    case 'u':
        System.out.println(letter + " là nguyên âm");
        break;
    case 'e':
        System.out.println(letter + " là nguyên âm");
        break;
    case 'o':
        System.out.println(letter + " là nguyên âm");
        break;
    case 'a':
        System.out.println(letter + " là nguyên âm");
        break;
    case 'i':
        System.out.println(letter + " là nguyên âm");
        break;       
    default:
        System.out.println(letter + " không phải nguyên âm");
        break;
}
```

# Bài 4
```java
for (int times = 10; times > 0; times --)
  System.out.println("alo");
}
```

# Bài 5

```java
for (int i = 0; i > 0 $$ i <= 100; i++) {
  if (i % 7 == 0) {
    continue;
    }
    System.out.println(i);
 }
}
```


