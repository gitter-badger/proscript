# Proscript
A weakly-typed, object-oriented, imperative, server-side programming language and runtime with event-driven architecture.

## Sample code

```JAVA
namespace Hello.World

global Main
    const EXCL_MARK is '!'
    
    private hello is 'Hello'
    private world is 'World'
    
    public static @construct(Map argv = [])
        instance is Main
        instance.showHelloWorld()
    
    private showHelloWorld()
        stdout this.hello + this.world + Main:EXCL_MARK
```

## Current status
A language specification is in-progress draft. It will be published in this repository.
Work on basic interpreter has been started.

## License
Language runtime components, standard library and specification are all licensed under the terms and conditions of Apache 2.0 license.
