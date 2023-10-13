# Newton
#include<stdio.h>
void main()
{
float u,a,t;
printf("enter initial velocity:-");
scanf("%f",&u);

printf("enter acceleration:-");
scanf("%f",&a);

printf("enter time:-");
scanf("%f",&t);

float v=u+a*t;
printf("The final velocity is %f\n",v);

float s=u+a*t*t;
printf("The distance travelled is %f\n",s);

}









