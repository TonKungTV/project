#include <stdio.h>
#include <conio.h>
#include <string.h>
int main()
{
    char x;
    int num1 = 0;
    int age;
    char str[3][50], name, surname;
    printf("Please login first :\n");
    for (int name = 1; name <= 1; name=name+1)
    {
        printf("Enter your name : ");
        gets(str[name]);
    }
    for (int surname = 1; surname <= 1; surname=surname+1)
    {
        printf("Enter your surname : ");
        gets(str[surname]);
    }
    for (int age = 1; age <= 1; age=age+1)
    {
        printf("Enter your age : ");
        gets(str[age]);
    }
    printf("=====Welcome=====");
    do
    {
        fflush(stdin);
        printf("\nDo you want to buy \n>>>> press 1 >>>> ");
        scanf("%d", &x);
    } while (x != 1);
    // system("cls");
    printf("Welcome to menu >>>> ");
    printf("\n========MENU========");
    printf("\n 1 : Foods ");
    printf("\n 2 : Snacks");
    printf("\n 3 : Drinks");
    printf("\n 4 : Exit");
    printf("\n-Choose-:");
    scanf("%d", &num1);
    if (num1 = 1)
    {
        Food();
    }
    else if (num1 = 2)
    {
        Snacks();
    }
    else if (num1 = 3)
    {
        Drinks();
    }
    else if (num1 = 4)
    {
        main();
    }
    else
    {
    }

    return 0;
}

Food()
{
    int food = 0;
    float food1=20.00,food2=15.00,food3=30.00;
    float money;
    float torn;
    char ch;

    printf("\n========MENU FOOD========");
    printf("\n1.Rice");
    printf("\n2.Mama");
    printf("\n3.Steak");
    printf("\n-Choose-:");
    scanf("%d", &food);

    switch (food)
    {
    case 1:
        printf("\n========MENU FOOD========");
        printf("\nName: Rice ");
        printf("%.2f", food1);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Rice ");
            printf("Total : %.2f", food1);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - food1;
            printf("Torn %d Bath",torn);
            break;
        }
        break;
    case 2:
        printf("\n========MENU FOOD========");
        printf("\nName: Mama ");
        printf("%.2f", food2);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Mama ");
            printf("Total : %.2f", food2);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - food2;
            printf("Torn %.2f Bath",torn);
            break;
        }
        break;
    case 3:
        printf("\n========MENU FOOD========");
        printf("\nName: Steak ");
        printf("%.2f", food3);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Steak ");
            printf("Total : %.2f", food3);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - food3;
            printf("Torn %.2f Bath",torn);
            break;
        }
        break;
        
    default:
        printf("Error");
        // break;
    }
}

Snacks()
{
    int snack = 0;
    float snack1=20.00,snack2=9.00,snack3=15.00;
    float money;
    float torn;
    char ch;
    printf("\n========MENU SNACK========");
    printf("\n1.Lays");
    printf("\n2.Euro");
    printf("\n3.Snackjack");
    printf("\n-Choose-:");
    scanf("%d", &snack);

    switch (snack)
    {
    case 1:
        printf("\n========MENU SNACK========");
        printf("\nName: Lays ");
        printf("%.2f", snack1);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Lays ");
            printf("Total : %.2f", snack1);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - snack1;
            printf("Torn %d Bath",torn);
            break;
        }
        break;
    case 2:
        printf("\n========MENU SNACK========");
        printf("\nName: Euro ");
        printf("%.2f", snack2);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Euro ");
            printf("Total : %.2f", snack2);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - snack2;
            printf("Torn %.2f Bath",torn);
            break;
        }
        break;
    case 3:
        printf("\n========MENU SNACK========");
        printf("\nName: Snackjack ");
        printf("%.2f", snack3);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Snackjack ");
            printf("Total : %.2f", snack3);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - snack3;
            printf("Torn %.2f Bath",torn);
            break;
        }
        break;
        
    default:
        printf("Error");
        // break;
    }
}
Drinks()
{
    int drink = 0;
    float drink1=20.00,drink2=15.00,drink3=30.00;
    float money;
    float torn;
    char ch;
    printf("\n========MENU DRINK========");
    printf("\n1.Oishi Sprakling Green Tea");
    printf("\n2.Coke Soft Drink Original");
    printf("3.Pepsi");
    printf("\n-Choose-:");
    scanf("%d", &drink);

    switch (drink)
    {
    case 1:
        printf("\n========MENU DRINK========");
        printf("\nName: Oishi Sprakling Green Tea ");
        printf("%.2f", drink1);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Oishi Sprakling Green Tea ");
            printf("Total : %.2f", drink1);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - drink1;
            printf("Torn %d Bath",torn);
            break;
        }
        break;
    case 2:
        printf("\n========MENU DRINK========");
        printf("\nName: Coke Soft Drink Original ");
        printf("%.2f", drink2);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Coke Soft Drink Original ");
            printf("Total : %.2f", drink2);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - drink2;
            printf("Torn %.2f Bath",torn);
            break;
        }
        break;
    case 3:
        printf("\n========MENU DRINK========");
        printf("\nName: Pepsi ");
        printf("%.2f", drink3);
        printf("\n Do you want to Buy [Y] or [N] >>> ");
        scanf("%s", &ch);
        switch (ch)
        {
        case 'Y':
        case 'y':
            printf("       Bill");
            printf("\nName: Pepsi ");
            printf("Total : %.2f", drink3);
            printf("\nInput Money :> ");
            scanf("%f", &money);
            torn = money - drink3;
            printf("Torn %.2f Bath",torn);
            break;
        }
        break;
    default:
        printf("Error");
        // break;
    }

}
