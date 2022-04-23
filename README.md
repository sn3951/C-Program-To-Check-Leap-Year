#include <stdio.h>
int main()
{
int y;
printf("Enter year: ");
scanf("%d",&y);
 if(y % 4 == 0)
     {
     if( y % 100 == 0)
     {
     if ( y % 400 == 0)
     printf("is a Leap Year", y);
     else
     printf("is not a Leap Year", y);
     }
     else
     printf("is a Leap Year", y );
     }
     else
     printf("is not a Leap Year", y);

   return 0;
}
