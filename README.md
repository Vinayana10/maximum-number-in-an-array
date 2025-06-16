# maximum-number-in-an-array
#include <stdio.h>


int main()
{
   int max,i,n;
   int a[100];
   printf("enter n value:");
   scanf("%d",&n);
   printf("enter 5 values:\n");
   for(i=0;i<n;i++){
       scanf("%d",&a[i]);
   }
   max=a[0];
   for(i=1;i<n;i++)
   {
       if(a[i]>max){
           max=a[i];
       }
     
   }
   printf("max num= %d",max);
}
