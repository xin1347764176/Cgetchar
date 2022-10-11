# Cgetchar
读取会有\n回车


#include <string.h>

int main() {



	int ret = 0;
	char password[20] = { 0 };
	scanf("%s" , password);
	if((ret = getchar())!='\n')//get'n'
	{
		;
	}
	ret = getchar();
	if (ret == 'Y') {
		printf("yes");

	}
	else{
		printf("no");

	}
	return 0;
}
