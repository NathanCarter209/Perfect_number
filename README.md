# Perfect_number
This is a code for whether the number is perfect or not.
```
int i, sum = 0, num;
printf("\n Enter your number : ");
scanf("%d", &num);
```
In this part we initialise the values for the code and we take a **num** as a user defined.
```
for ( i = 1; i <= num/2; i++)
```
In this part we need to initialse a loop here so that the loop will keep on checking the number for perfect number till 100 
to check perfect numbers above 100 we use Euclid–Euler theorem. So lets not use this theoram in this code.
```
if (num%i == 0)
        {
             sum += i;       
        }
```
In this part we 
```
if (sum == num && num > 0)
    {
        printf("%d is the PREDECT NUMBER\n", num);
    }
    else
    {
        printf("%d is NOT A PERFECT NUMBER\n", num );
    }
```
In this part we need initialise if-else statement for 1
