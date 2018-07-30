# Universal Data Shorthand (a.k.a. UDatS)

![license MIT](https://img.shields.io/badge/license-MIT-green.svg)

Language-agnostic shorthand notation for representing the type and 
structure of data in documented code as clearly and efficiently as 
possible.

---------------------------------------------------------------------------------------

# READ THIS FIRST (SERIOUSLY)
Universal Data Shorthand (UDatS) is a shorthand notation for representing the structure
of the data in your programs. UDatS is intended to be used in to communicate patterns 
(like how many times a given type is allowed to occur in a container, more on that later),
and to shorten lengthy documentation of return types, parameters or whatever you need to 
only a few words.

This project does not, and most likely never will, provide any actual code. UDatS is simply
a format for you to integrate into your documentation.

## Note on the word *Universal*
The word *Universal*, does NOT mean that all HUMANS will understand
UDatS, if you include it in your documentation. I would highly recommend
linking to this repository in the beginning of your documentation, to
clear up confusion.

## Motivation and Concept
The UDatS format uses the basic syntax for the language being documented (along with 
some special characters and keywords), in order to make it easier, and less error-prone
to document the various simple data formats that programmers use every day. These simple
data structures may seem easy to understand when a coder creates it, but the rules that
describe what lists/arrays or dictionarys/maps are expected and in what order can be hard
to put into words.

UDatS allows programmers to easily convey the patterns in these _simple_ data formats, by
using concepts similar to those found in regular expressions.

# Fundamentals
If you did not read the above section titled **READ THIS FIRST**, go back and read that now.

This documentation assumes that you are comfortable with the following basic programming concepts: 
- *arrays* (or *lists* in some languages like Python)
- *dictionaries* (also called *maps*, *assosiative arrays*, and *symbol tables*)
- *types* and *constructors* (if applicaple to your programming language)
- *functions* (often called *methods*) and *return values*

Some familiarity with *regular expressions* (in any programming language) is helpful but not required.
