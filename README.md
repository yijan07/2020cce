# 2020cce

 ## 第一個程式
 ```c
 #include <stdio.h>
 int main()
 {
	 int n;
	 scanf("%d",&n);
	 printf("%d=50*%d+5*%d+1*%d\n",n,n/50,(n%50)/5,(n%50)%5);
 }
 ```
 ## 第二個程式
 ```c
 #include <stdio.h>
 int main()
 {
	 int n,a=0;
	 scanf("%d",&n);
	
	 for(int i=1;i<=n;i++){
		 if(n%i==0)
		 a++;
    }
	 printf("%d\n",a);
 }
 ```
