---
marp: true
size: 16:9
paginate: true
header: "ヘッダー"
footer: "フッター"
headingDivider: 2
style: |
    section::after {
        content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
    }

---
<!-- _paginate: false -->
<!-- _class: top -->

# タイトル



## C

``` C
 #include <stdio.h>

 int main(void)
 {
     printf("Hello, world!\n");
     return 0;
 }
```

## C++

``` C++
#include <iostream>

using namespace std;

int main(){
  cout << "Hello world!" << endl;
  return 0;
}
```

## C#

``` C#
using System;

public class Hello{
  public static void Main(){
    Console.WriteLine("Hello world!");
  }
}
```




# おしまい
<!-- _paginate: false -->
<!-- _class: bottom -->
