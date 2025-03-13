# h1 tag
## h2
### h3 
#### ㄱ가ㅏ
나나
다ㅏ
다다ㅏ
다다ㅏㄷ
# 다다#
###### 다다
------
---
-
==
+ 가가가
- 나나나
* 나나
1. 나난
2 나나
2. 나나

```
```
``` java
lass Prime {

    public static void main(String[] args) {

        int low = 20, high = 50;

        while (low < high) {
            if(checkPrimeNumber(low))
                System.out.print(low + " ");

            ++low;
        }
    }

    public static boolean checkPrimeNumber(int num) {
        boolean flag = true;

        for(int i = 2; i <= num/2; ++i) {

            if(num % i == 0) {
                flag = false;
                break;
            }
        }

        return flag;
    }
}
```










ublic class Prime {

    public static void main(String[] args) {

        int low = 20, high = 50;

        while (low < high) {
            if(checkPrimeNumber(low))
                System.out.print(low + " ");

            ++low;
        }
    }

    public static boolean checkPrimeNumber(int num) {
        boolean flag = true;

        for(int i = 2; i <= num/2; ++i) {

            if(num % i == 0) {
                flag = false;
                break;
            }
        }

        return flag;
    }
}










ublic class Prime {

    public static void main(String[] args) {

        int low = 20, high = 50;

        while (low < high) {
            if(checkPrimeNumber(low))
                System.out.print(low + " ");

            ++low;
        }
    }

    public static boolean checkPrimeNumber(int num) {
        boolean flag = true;

        for(int i = 2; i <= num/2; ++i) {

            if(num % i == 0) {
                flag = false;
                break;
            }
        }

        return flag;
    }
}