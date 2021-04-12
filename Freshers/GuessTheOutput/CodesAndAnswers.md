## "Guess the output of given codes" type questions

1. What will be output of following code?
```cpp
int * f(){
    int a = 10;
    int *b = &a;
    return b;
}

main(){
    int *temp = f();
    cout<<*temp<<endl;
    return 0;
}
```
Answer: Either 0 or garbage value, as it will be a [dangling pointer.](https://www.javatpoint.com/dangling-pointers-in-c#:~:text=Sometimes%20the%20programmer%20fails%20to,the%20value%20of%20the%20pointer.)