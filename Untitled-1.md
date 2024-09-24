# 2024090908012-但家利-CS-01
## 第一个程序
1. 高级计算机语言 优点：易于学习，编写；可读性强；适用性广。
                 缺点：性能较低级计算机语言较慢；对硬件控制有限。
   低级计算机语言 优点：性能较高级计算机语言较快；对硬件控制更好。
                 缺点：难以学习，编写；可读性差；适用性差。
   个人观点：更喜欢高级计算机语言。因为可能本人更习惯于从简单的方面入手，之后再突破较难的部分。
2. `#include <stdio.h>` :是一个预处理指令，用于使编译器在编译程序前包含标准输入输出库头文件`stdio.h`,从而定义一系列输入输出指令，如`printf()`等。
   `int main()` : main是C程序的主函数，每个C程序都要有一个主程序；`int`表明main的返回值是整数。
   {} ：表程序的开始与结束。
   `printf("Hello,World!")` :表输出 Hello,World! 这个内容。
   `return 0` : 表明程序结束，同时用于判断程序是否有误。
3. `return 0`
4. 整数 ；约定俗成，`int`作为最基本的数据类型，较为简单且兼容性好（相较于`void`）
5. 如图为所求

## 基础语法运用
<pre>
#include <stdio.h>   
 int main()    
 {   
    long int code;    
    printf("Show me your code,please.\n");    
    scanf("%d",&code);    
    for(;1;)    
    {   
      if(code>=100000 && code<=999999)   
       {   
            printf("I am super hacker!");   
            return 0;    
        }   
        else   
        {   
            printf("Fake code!\n");   
            scanf("%d",&code);    
        }     
    }     
 }    
</pre>

## 课后作业
<pre>
 #include <stdio.h>
 int main()
 {
   long int m,n,r;
   scanf("%ld %ld",&m,&n);
   r=m%n;
   while(r!=0)
       {
           r=m%n;
           m=n;
           n=r;
       }
       printf("%ld",m);
 }
</pre>


