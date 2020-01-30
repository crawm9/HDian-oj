# HDian-oj
杭电水题100

1000.A + B Problem
Calculate A + B.

Input
Each line will contain two integers A and B. Process to end of file.

Output
For each case, output A + B in one line.

Sample Input
1 1

Sample Output
2

code:
#include<stdio.h>
int main()
{
int a,b;
while(scanf("%d %d",&a,&b) != EOF)//有很多输入，直到文件结尾
printf("%d\n",a+b);
return 0;
}
