//watch(Sorry, not my watch)*


#include <stdio.h>
#include <stdlib.h>
int main()

 {
    int h,m,s;
    int d=1000;
    printf("Cейчас время :\n");
    scanf("%d%d%d",&h,&m,&s);
    if(h>12 || m>60 || s>60 )
       {
        printf("Ошибка! \n");
        exit(0);
       }
            while(1)
    {
       s++;
       if(s>59)
         {
            m++;
            s=0;
         }
        if(m>59)
       {
            h++;
            m=0;
       }
       if(h>12)
       {
            h=1;
       }
       printf("\n Время:");
       printf("\n %02d:%02d:%02d,h,m,s");
       int sleep(d);
       system("clear");
    }
}
