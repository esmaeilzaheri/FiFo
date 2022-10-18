# FiFo
Project FiFo By Esmaeil 


#include
#include
void main()
{
int mat[10][3],mat1[10][4];
int et,st,i,j,n;
int sum,sum1,tw,tr,ts;

for(i=0;i<10;i++)
  for(j=0;j<4;j++)
     mat1[i][j]=-1;
 
printf("please enter number of process = ");
scanf("%d",&n);

for(i=0;i {
    printf("process p%d",i);
    printf("\n");
    printf("enter time is:=");
    scanf("%d",&et);
    printf("service time is:=");
    scanf("%d",&st);
    printf("\n");
    mat[i][0]=i;
    mat[i][1]=et;
    mat[i][2]=st;
 }
