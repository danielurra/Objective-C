# Objective-C
Objective-C is an OOP (object-oriented programming) for Apple's iOS and OS X platforms.</br>
<center ![objective-c](https://github.com/danielurra/Objective-C/assets/51704179/11818194-b341-4eb4-8450-8fde639f6196)/></br>
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
        // insert code here...
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

