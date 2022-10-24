# An Introduction to GD Modding (using Geode)

Hello everyone! This is **an introduction to GD Modding (using Geode)**, a handbook that covers all of the essentials of GD Modding. To follow along with this handbook, you will need to have [**Geode** installed](/docs/info/installation.md). This handbook is written as a **tutorial for beginners**, though even if you are an experienced GD modder already, getting a fresh-up on the basics can never do harm. Even if for some reason you don't use Geode, this handbook still contains **general information about modding and GD modding specifically**, however all practical code examples and the code project we will build later will use Geode.

### Prerequisites

Do note that while this handbook is written for people with little to no previous experience modding GD, **previous programming and computing knowledge is assumed**. It is highly recommended that before you start GD modding, you should at the very least know how to use **C++**. (Knowledge of other programming languages is also good, but the closer to C++ the better)

If you're **unsure** that you have sufficient programming skills, here's a **list of concepts you should at the very least know**:

 * Control flow
 * Variables
 * Functions
 * Data types
 * Classes
   * Inheritance (including multiple inheritance)
 * Namespaces
 * The C++ Standard Library

**Other concepts that are very good to know beforehand but not strictly required**:

 * Pointers & references (if you don't know how pointers work, you can get through this tutorial, but you will also be in big trouble later on)
 * Macros and the C++ Preprocessor
 * X86 Assembly (doesn't mean you should speak or read it fluently; just know what it is)
 * Difference between compile-time and runtime
 * Reverse enginering (the basics of using Ghidra will be explained in Chapter TODO)

If some of the items in the list aren't familiar to you, **you should read up on some online resources first**. A good place to start is to just write "C++ tutorial" in Google and see what comes up. If only some specific parts are unfamiliar, for example you don't know how namespaces work, search for "C++ namespaces".

### How to read this handbook

It is recommended to read through the book chapter-by-chapter. Important concepts and keywords are highlighted in **bold**. Variables, functions, registers and all other code entities are written like `this`. Code blocks look like this:

```cpp
#include <iostream>

int main() {
    std::cout << "Hi mom!\n";
}
```

The language presented in the code blocks should be stated right before or after the block in the text, but the majority of code blocks use C++.

> :warning: This is what a warning looks like. If you see one of these boxes, **pay close attention**; it contains tips about how to **avoid common mistakes** in modding.

> :information_source: This is what an info box looks like. It contains **general information** about the current topic that you might find useful.

> :green_book: Boxes like this contain links to **further reading** materials for the interested.

Sometimes the text has notes like this [Note 1]. They are explained at the end of the paragraph, or at the end of the text at the **Notes** section.

> [Note 1] This is what an **explanation of a note** looks like.

### Ready, set, go!

**And with that, let us start with [Chapter 1](/docs/handbook/chap1)!**
