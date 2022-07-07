//# factorial_by_recursion
//factorial_by_recursion using c


#include<stdio.h>
int main()
{
	int n,res;
	printf("enter the number: ");
	scanf("%d",&n);
	res = (int)fact(n);
	printf("factorial of %d is %d: ",n,res);
	
}
 fact(int n){
 	int res;
 	if(n==0){
 		res=1;
	 }
	 else{
	 
	res=n*fact(n-1);
     }
	return res;
}
