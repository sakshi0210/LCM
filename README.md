# LCM
Find LCM of number
#include<stdio.h>
int lcma(int,int);
main()
{int a;
int b;
int lcm;
printf("input 1st no.=");
scanf("%d",&a);
printf("input 2nd no.=");
scanf("%d",&b);
lcm=lcma(a,b);
printf("LCM of %d and %d is %d",a,b,lcm);
return 0;
}
int lcma(int a,int b)
{
	static int w=1;
	if(w%a==0 && w%b==0){return w;
	}
	else{ w++;
	int lcma(int a,int b);
	return w;
	
	
	}
}
