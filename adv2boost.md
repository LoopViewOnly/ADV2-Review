# Loop

![alt text](BLUE-Logo.png)

# Advanced-2 Course Review

### Random Numbers

```cs
Random rnd = new Random();
int x = rnd.Next(10); //---> x = 0 - 9
int y = rnd.Next(30,50); //---> y =  30 - 49
```

<hr><hr>

### Arrays

```cs
int[] arr1 = {1 , 7 , 4 , 0 , -4 , 6 };
double[] arr2 = {2.4 , 7.8 , 2.0 , -5.214};
string[] arr3 = {"Jeries", "Joseph","Peter","Loop","Bata"};

int size1 = arr1.Lenght; // --->  6
int size2 = arr2.Lenght; // --->  4
int size3 = arr3.Lenght; // --->  5
```

arr1 [0] = 1 <br>
arr1 [1] = 7 <br>
arr1 [2] = 4 <br>
arr1 [5] = 6 <br>
arr1 [size1 - 1] = 6 <br>

<hr>

##### Print elemnts in arrays

```cs
for( int i=0 ; i < arr1.Length ; i++)
{
    Console.WriteLine( arr1 [i] );
}
```

<hr> <hr>

#### Functions

void = فراغ

```cs
static void sayHi()
{
    Console.WriteLine("Hello");
}

static double average (double a, double b , double c)
{
    return ((a+b+c) / 3);
}

static char firstChar(string name)
{
    return name[0];
    //this function takes a name as parameter and return the fist char in the name
}
```
