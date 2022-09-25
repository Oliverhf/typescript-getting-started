# TypeScript-Getting-Started

NOTES:

## Interfaces vs. Classes

|Inferfaces | Classes |
| --- | ----------- |
| Define a new type | Define a new type |
| Properties (sigantures) | Properties (with implementation) |
| Methods (signatures) | Methods (with implementation)
| Cannot be instantiated | Can be instantiated


## Class Members

* Method implementations
* Property implementations
* Accessors (getters and setters)
* Access modifiers
    - Public
    - Private
    - Protected (it may only be accessed inside the class or any classes that inherit from the class)


## Extending a Class

```
class WebDeveloper extends Developer {
    favoriteEditor: string;
    writeTypeScript(): void {
        // write awesome code
    }
}

let webdev: WebDeveloper = new WebDeveloper();

```

* A common practice is to design classes to implement interfaces.
