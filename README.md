#include<stdio.h>
int main()
{
    int n,a[10],sum=0;
    float avg;
    printf("enter n:");
    scanf("%d",&n);
    for(int i=0;i<n;i++)
    scanf("%d",&a[i]);
    for(int i=0;i<n;i++)
    sum+=a[i];
    avg=sum/n;
   printf("sum=%d,average=%f",sum,avg);
    return 0;
}

output:
enter n:5
3
6
6
5
4
sum=24 avg=4.000000
