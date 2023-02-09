#include<stdio.h>
int main()
{
	int i,j,a[10],n,temp;
	printf("enter the no of elements");
	scanf("%d",&n);
	for(i=0;i<n;i++){
		scanf("%d",&a[i]);
	}
	for(i=1;i<n-1;i++){
		for(j=i;j>0 && a[j-1]>a[j];j--){
			temp=a[j];
			a[j]=a[j-1];
			a[j-1]=temp;
		}
	}
	for(i=0;i<n;i++){
	printf("%d\n",a[i]);
	}
}
