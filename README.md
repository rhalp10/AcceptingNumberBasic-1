# AcceptingNumberBasic1
[x]Accepting Number  And Display If Its Positive or Negative
The Code is inside of the document with sample screenshoots 
# Code
```
#include<iostream.h>
#include<conio.h>
void main ()

{clrscr();

    int i,number,count;

    count = 0;

    for (i = 1; i <=10; i = i + 1)
{

    cout << "Enter An Integer Value:";

    cin >> number;

    if ( number <= 0) i = i + 1;

    else cout << "Positive" << endl;

    if ( number >= 0) i = i + 1;

    else cout << "Negative" << endl;

    }

getch();
}

```

