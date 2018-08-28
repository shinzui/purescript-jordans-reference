# Console Lessons

After one introduces the "Hello World" app in a language tutorial/textbook, they usually introduce additional programming concepts by writing a console-based program, a program that can receive user input and that outputs something based on that input. We will follow suit.

In this folder, we'll continue teaching some FP concepts, such as:
- Error Handling
- State
- Custom Type Warnings/Failures
- Testing
- Benchmarking

In the process, we'll also explain some basic data types along the way:
  - `Maybe a`
  - `Either a b`
  -

When compiling these examples, you will likely see a warning like below. This is supposed to happen, so don't be alarmed:
```
Warning found:
in module ConsoleLessons.CustomTypeErrors.TypeClassInstances
at src/03-Custom-Type-Errors/04-Type-Class-Instances.purs line 41, column 1 - line 41, column 23

  A custom warning occurred while solving type class constraints:

    No worries! This warning is supposed to happen!

    [Some warning message here...]


in value declaration warnInstance

See https://github.com/purescript/documentation/blob/master/errors/UserDefinedWarning.md for more information,
or to contribute content related to this warning.
```

At times, we'll hide some types/functions from you, so that you can focus on learning rather than explaining why/how something works. If you are curious to look at it later, the helper code can be found in the "Helper-Code" folder.