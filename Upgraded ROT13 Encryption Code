#include <stdio.h>

void encryption(){

    char message[1000000];
    printf("Write something and I'll encrypt it.\n");
    while(getchar() != '\n');
    fgets(message, 1000000, stdin);

    for (int i = 0; i < 1000000; i++)
    {
        printf("%03d",message[i]+13);
        if (message[i+1] == '\0')
        {
            break;
        }
    }
    printf("\n");
}

void decryption(){

    int number_array_decrypt[1000000];
    printf("Enter the numbers:\n");

    int i = 0;
    
    while (scanf("%3d",&number_array_decrypt[i]) == 1)
    {
        i++;
    }

    for (int j = 0; j < i; j++)
    {
        printf("%c",number_array_decrypt[j]- 13);
    }

    printf("\n");
    fflush(stdout);
}


int main(){

    char answer;
    printf("Encryption(E) / Decryption(D)\n");
    scanf("%c",&answer);

    if (answer == 'E')
    {
        encryption();
    }
    else if (answer == 'D')
    {
        decryption();
    }
    else{
        printf("Invalid. Please try again\n");
    }

    return 0;
}
 
