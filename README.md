# C_teaching
<stdio.h>	Реализует основные возможности ввода и вывода в языке Си. Этот файл содержит весьма важную функцию printf.

<math.h>	Для вычисления основных математических функций

<stdlib.h>	Для выполнения множества операций, включая конвертацию, генерацию псевдослучайных чисел, выделение памяти, контроль процессов, окружения, сигналов, поиска и сортировки.

<time.h>	Для конвертации между различными форматами времени и даты.


--------------

переменные

    char symbol1; int cnt; float adc_val;

    char symbol1 = 'c', symbol2 = 'f', symbol3= 'h';
    int cnt = 589;
    float adc_val = 124.54f;
    
массивы

    unsigned char i;
    int n[6];
    n[0] = 10; n[1] = 25; n[2] = 33; n[3] = 71; n[4] = 54; n[5] = 99;
  
    int n[6] = {10, 25, 33, 71, 54, 99};
    char str1[10] = {'H', 'e', 'l', 'l', 'o', '!', '\0'};
    char str1[10] = {"Hello!"};


    int n[3][4] = {{10, 25, 33, 71},
                   {45, 77, 44, 18},
                   {38, 84, 21, 99}};
константа     

    #define VAR_CONST1 15

-------------------
ввод-вывод 

      scanf("%d", &n);
      printf("n %d\r\n", n);

-------------------
цикл

    while(i)
      {
        printf("i = %d\r\n", i);
        i--;
      }

    do
      {
        printf("i = %d\r\n", i);
        i--;
      } while(i);


    for(i=0; i<10; i++)
      {
        printf("i = %d\r\n", i);
      }
      
-------------------
условие

    if(n<10)
      {
        printf("You have entered a number less than 10\r\n");
      }
      else if(n<=30)
      {
        printf("You entered a number between 10 and 30\r\n");
      }
      else
      {
        printf("You entered a number greater than 30\r\n");
      }

                
-------------------
переключатель 

    switch(n)
    {
      case 10:
        printf("You entered number 10.\r\n");
        break;			
      case 20:
        printf("You entered number 20.\r\n");
        break;			
      case 30:
        printf("You entered number 30.\r\n");
        break;        
      case 40:
        printf("You entered number 40.\r\n");
        break;
      case 50:
        printf("You entered number 50.\r\n");
        break;
      default:
        printf("The entered number does not match with any of the proposed.\r\n");
        return 0;
    }



  
