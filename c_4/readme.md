# 2023-3-23 4주차 C언어 수업
```

#include <stdio.h>
int main()
{
int x,y,re;
int n1=0, n2=0, n3=0;
scanf("%d %d", &x, &y);

n1=x*(y%10);
n2=x*(y/10%10);
n3=x*(y/100);


printf("%d\n",n1);
printf("%d\n",n2);
printf("%d\n",n3);

    return 0;
}
