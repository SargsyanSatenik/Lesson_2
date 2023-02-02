# Methods

https://learn.microsoft.com/en-us/cpp/c-language/recursive-functions?view=msvc-170

```
int factorial( int num );      /* Function prototype */

int main()
{
    int result, number;
    result = factorial( number );
}

int factorial( int num )      /* Function definition */
{
        if ( ( num > 0 ) || ( num <= 10 ) )
        return( num * factorial( num - 1 ) );
}
```
