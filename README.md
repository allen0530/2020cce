# 2020cce
## 第一個程式
```c
#include <stdio.h>
int main()
{
	int a , b, c, d;
	scanf("%d",&a);
	printf("%d=50*%d+5*%d+1*%d\n",a,a/50,a%50/5,a%50%5/1);
	



}
```
## 第二個程式
```c
#include <stdio.h>
int main()
{
	int a,i,b=0;
	scanf("%d",&a);
	
	for(int i=1;i<=a;i++)
	{
		if(a%i==0)
		{
		b++;
		
		}
		}
	printf("%d\n",b);
	
		



}
```






## 第三個程式
```c
#include <stdio.h>
int main()
{
	int a,i,b=0;
	
	for(int i=0;i<10;i++)
	{
		scanf("%d",&a);
		if(a%3==0)
			b++;
	}
	printf("%d\n",b);
	
	





}
```




## 第四個程式
```c
#include <stdio.h>
int main()
{
	int a;
	scanf("%d",&a);
	if(a>=90) printf("A\n");
	else if(a<90&&a>=80) printf("B\n");
	else if(a<80&&a>=60) printf("C\n");
	else printf("F\n");
	




}
```






## 第五個程式
```c
#include <stdio.h>
int main()
{
	int a,b,i,ans=1;
	scanf("%d%d",&a,&b);
	for(int i=1;i<=b;i++)
	{
		if(a%i==0 && b%i==0)
			ans=i;
	}
	printf("%d %d\n",a/ans,b/ans);
	




}
```
## 第六個程式
```c
#include <stdio.h>
int main()
{
    int n1=10,n2=20,n3=30;
    printf("n1=%d n2=%d n3=%d\n",n1,n2,n3);

    int *p=&n1;
    *p=200;
    printf("n1=%d n2=%d n3=%d\n",n1,n2,n3);


}
```







## 第七個程式
```c
#include <stdio.h>
int main()
{
    int n1=10,n2=20,n3=30;
    printf("n1=%d n2=%d n3=%d\n",n1,n2,n3);

    int *p=&n1;
    *p=200;
    printf("n1=%d n2=%d n3=%d\n",n1,n2,n3);

    int *p2=&n3;
    *p2=300;
    printf("n1=%d n2=%d n3=%d\n",n1,n2,n3);
}
```











## 第八個程式
```c
```
