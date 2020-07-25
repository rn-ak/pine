# 정보올림피아 문제 풀이반복제어문3 - 형성평가 9

#include <stdio.h>
 
int main()
{
  int n, i,j;
  int num=1;
 
  scanf("%d", &n);
 
  for(i=0; i<n; i++)
  {
    for(j=0; j<i; j++)
    {
      printf("  ");
    }
    for(j=0; j<n-i; j++)
    {
      printf("%d ", num++);
    }
     
    printf("\n");
  }
 
}
