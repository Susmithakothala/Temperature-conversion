# include<stdio.h>
int main()
{
float c,f,ce ,fa;
printf ("\n Enter a celcius value to convert to farenheit ");
scanf ("%f" ,&c);
fa = (1.8* c) + 32;
printf ("\n\t %0.2 f Celcius = %0.2 f farenheit " ,c,fa );
printf ("\n Enter a farenheit value to convert to celcius ");
scanf ("%f" ,&f);
ce = (f -32) / 1.8;
printf ("\n\t %0.2 f Farenheit = %0.2 f Celcius ",f,ce );
return 0;
}
Output:
Compilation :[-----]$ cc filename .c
Execution :[----] $ ./a. out
Enter a celcius value to convert to farenheit
36
36.00 Celcius =96.80 Farenheit
Enter a farenheit value to convert to celcius
96.8
96.80 Fahrenheit=36.00 Celsius