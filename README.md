#include<stdio.h>
int main(){
    int userchoice;
    float balance=5000, temp;
    printf("User Choice \n");
    printf("1. Deposit\n");
    printf("2. Withdrawl\n");
    printf("3. Balance Check\n");
    printf("4. Exit\n");
    scanf("%d",&userchoice);
    switch(userchoice){
        case 1:printf("Enter amount to deposit\n");
        scanf("%f",&temp);
        balance=balance+temp;
        break;
        case 2:printf("Withdraw \n");
        scanf("%f",&temp);
        break;
        case 3:printf("Balance = %f",balance);
        break;
        case 4:printf("Exit\n");
        break;
        default:
        printf("Invalid choice\n");
    }
    return 0;
}
