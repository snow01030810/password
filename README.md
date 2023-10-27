# password
#include <stdio.h>
#include <string.h>
int main() 
{
	int i = 0;
	char  password[20] = {0};
	for (i = 0; i < 3; i++)
	{
		printf("password:> ");
		scanf_s(" % s", password);
		if (strcmp(password, "0") == 0)
		{
			printf(":D");
			break;
		}
		else
		{
			printf(":(");
		}
	}
	if (i == 3)
		printf(": <");
	return 0;
}
