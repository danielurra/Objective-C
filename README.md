# Objective-C
Objective-C is an `Object-oriented Programming` language for Apple's iOS and OS X platforms.</br>
It expands the old good **C** and because of that Objective-c is a superset of **C**.
![objective-c](https://github.com/danielurra/Objective-C/assets/51704179/11818194-b341-4eb4-8450-8fde639f6196)</br>
## My first console programm
![HelloWorld-objective-c](https://github.com/danielurra/Objective-C/assets/51704179/060e3807-ab9e-46cd-8f53-34ad9e1dd340)</br>
## Grab the code
```objective-c
//
//  main.m
//  MyFirstProgram
//
//  Created by mac user on 5/27/23.
//

#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    @autoreleasepool {
        NSLog(@"Hello, Objective-C!");
        NSLog(@"My first console App");

    }
    return 0;
}

```
## Compile
The Objective-C compiler is called **clang**, the following command builds an executable file called **TermApp**</br>
```objective-c
clang -fobjc-arc main.m -o TermApp
```
Automated Reference Counting (ARC), is a memory-management technique, the compiler flag **-fobjc-arc** tells the compiler to use ARC.
## Execute
```objective-c
./TermApp
```
![execute](https://github.com/danielurra/Objective-C/assets/51704179/dba1ced5-95a1-4a5b-9ce5-63f89603409a)

