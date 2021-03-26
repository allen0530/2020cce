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
#include <stdio.h>
int main()
{
    int n[3]={10,20,30};
    printf("n[0]=%d n[1]=%d n[2]=%d\n",n[0],n[1],n[2]);

    int *p=&n[0];
    *p=200;
    printf("n[0]=%d n[1]=%d n[2]=%d\n",n[0],n[1],n[2]);

    int *p2=&n[2];
    *p=300;
    printf("n[0]=%d n[1]=%d n[2]=%d\n",n[0],n[1],n[2]);
    p2=p;
    *p2=400;
    printf("n[0]=%d n[1]=%d n[2]=%d\n",n[0],n[1],n[2]);

    return 0;

}
```
## 第九個程式
```c
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printfAll(){
for(int i=0;i<5;i++)printf("%d ",a[i]);
   printf("\n");
   }
 int main()
 {

     printfAll();

     int* p=&a[2];
     *p=222;
     printfAll();
     p=p+2;
     *p=666;
     printfAll();
 }
```
## 第十個程式
```c
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printfAll(){
for(int i=0;i<5;i++)printf("%d ",a[i]);
   printf("\n");
   }
 int main()
 {

     printfAll();

     int* p=&a[2];
     *p=222;
     printfAll();

     p=p+2;
     *p=666;
     printfAll();

     p--;
     *p=555;
     printfAll();

 }

```
## 第十一個程式
```c
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printfAll(){
for(int i=0;i<5;i++)printf("%d ",a[i]);
   printf("\n");
   }
 int main()
 {

     printfAll();

     int* p=&a[2];
     *p=222;
     printfAll();
     printf("p心理小紙條的值是:%d\n",p);
     p=p+2;
     *p=666;
     printfAll();
     printf("p心理小紙條的值是:%d\n",p);
     p--;
     *p=555;
     printfAll();
     printf("p心理小紙條的值是:%d\n",p);
 }

```
## 第十二個程式
```c
#include <stdio.h>
#include <stdlib.h>
int a[10];
int main(){
int b[10];

int *p=(int*)malloc(sizeof(int)*10);

return 0;
}
```
## 第十三個程式
```c
#include <stdio.h>
struct POINT{
    float x,y;
};
 int main()
 {
     struct POINT a={4.1,3.2};
     printf("%f %f\n",a.x,a.y);
     return 0;;

 }
```
## 第十四個程式
```c
#include <stdio.h>
struct POINT{
    float x,y;
};
 int main()
 {
     struct POINT a={4.1,3.2};
     printf("%f %f\n",a.x,a.y);

     a.x=1;
     a.y=2;
     printf("%f %f\n",a.x,a.y);

     return 0;;

 }
```
## 第十五個程式
```c
#include <stdio.h>
struct DATA{
    int x,y;
}a[3];
struct DATA b={100,200};
 int main()
 {
     for(int i=0;i<3;i++){
        printf("a[%d]:%d %d\n",i,a[i].x,a[i].y);
     }
     printf("b: %d %d\n",b.x,b.y);
     struct DATA c;

     printf("c: %d %d ¹³¶Ã½X\n",c.x,c.y);

     c=b;
     printf("c: %d %d\n",c.x,c.y);


 }
```
## 第十六個程式
```c
#include <stdio.h>
struct DATA{
    int x,y;
}a[3];
struct DATA b={100,200};
 int main()
 {
     for(int i=0;i<3;i++){
        printf("a[%d]:%d %d\n",i,a[i].x,a[i].y);
     }
     printf("b: %d %d\n",b.x,b.y);
     struct DATA c;

     printf("c: %d %d ¹³¶Ã½X\n",c.x,c.y);

     c=b;
     printf("c: %d %d\n",c.x,c.y);


 }
```
## 第十七個程式
```c
#include <stdio.h>
struct POINT{
    float x,y,z;
};
struct POINT point[5]={{0,0,0},{1,0,0,},{0,1,0},{0,0,1},{1,1,1}};
 int main()
 {
     struct POINT * p=& point[0];
        printf("%.2f %.2f %.2f\n",p->x,p->y,p->z);

     p++;
      printf("%.2f %.2f %.2f\n",p->x,p->y,p->z);
      p++;
       printf("%.2f %.2f %.2f\n",p->x,p->y,p->z);


 }
```
## 第十八個程式
```c
#include <stdio.h>
int main()
{
    char line[10]="decline";
    char line2[10]={'p','r','o','p','e','r','\0'};
    printf("%s\n",line);
    printf("%s\n",line2);
    }
```
## 第十九個程式
```c
#include <stdio.h>
int main()
{
    char line[10]="decline";
    char line2[10]={'p','r','o','p','e','r','\0'};
    printf("%s\n",line);
    printf("%s\n",line2);
    char line3[]="majority";
    printf("%s\n",line3);
    char line4[]={'m','a','j','o','r','i','t','y'};
    printf("你看看你看看,現在印出來的line4:==%s==\n",line4);







}
```
## 第二十個程式
```c
#include <stdio.h>
int main()
{
    char line[5][10]={"decline","proper","majority","bullet","shop"};
    for(int i=0;i<5;i++){
        printf("%s\n",line[i]);
    }







}
```
## 第二十一個程式
```c
#include <stdio.h>
int main()
{
printf("請看看值是多少:%d",'\0');




}

```
## 第二十二個程式
```c
```
## 第二十三個程式
```c
```
