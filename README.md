# Code1
#include <stdio.h>
#include <string.h>

int main ()
{
	char string[100];
    printf("\n\t Enter the no.of string : ");
	scanf(“%d”,n);
  if (n<=0)
  printf("Invalid Input");
  	char temp;
	int i, j;
	int m = strlen(string[n]);
  
  for (i=0; i<n;i++)
  printf("\n\t Enter the string : ");
	scanf(“%s”,string[n]);
	for (i = 0; i < n; i++) {
		if (string[i] > string[i+1]) {
					temp = string[i];
					string[i] = string[i+1];
					string[i+1] = temp;
			}
	}
	}
