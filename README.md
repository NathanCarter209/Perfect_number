# Perfect_number
### This is a code for whether the number is perfect or not.
```
int i, sum = 0, num;
printf("\n Enter your number : ");
scanf("%d", &num);
```
- The code above is a simple program that asks the user to enter their number.
- The main function starts by declaring two variables: sum which will be used as an accumulator variable for adding numbers together, and num which will hold the value entered by the user.

```
for ( i = 1; i <= num/2; i++)
if (num%i == 0)
        {
             sum += i;       
        }
```
- The code loops through each of the numbers from 1 to num/2, and if it is divisible by that number, adds one to the sum.
- printf("\n Enter your number : "); scanf("%d", &num); for ( i = 1; i <= num/2; i++) The first line asks the user to input their desired value in order                for them to continue with the loop.
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
- It starts by declaring a variable called sum, which is initialized to 0.
- Next, the code checks if the inputted number is equal to zero and if so, prints out "(**num**) is the PERFECT NUMBER".
- If not then it will check if the inputted number is greater than or equal to one less than its own value (1).
- If so then it will print out "(**num**) is NOT A PERFECT NUMBER" because **num** does not make up a perfect number.
- The code will print the number **"num"** to the screen if it is a perfect number, otherwise, it will print **"0"**.
