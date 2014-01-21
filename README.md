java-code-conventions
=====================

Java Code Conventions and Formatting


# General

It is often useful to adopt common code conventions, almost when working on a team or on open source projects.  
In modern IDEs, the source code can also be automatically formatted, like in Eclipse.


# Eclipse

### How to import a code style ?

In Eclipse : __Window > Preferences > Java > Code Style > Formatter__

You can pick mine by example : [here](eclipse/eclipse-java5-codestyle.xml).  
As you can see, I don't like much the Sun or [K&R style](http://en.wikipedia.org/wiki/Indent_style#K.26R_style) of indentation. 
I prefer to adopt the [Allman style](http://en.wikipedia.org/wiki/Indent_style#Allman_style), 
where the opening and closing braces are aligned. 
 
It will be available within the current workspace.


### How to format source code ?

Right click in the source code, then Source > Format (shortcut : Ctrl + Shift + F).


# Other useful references

* [Google Java Style](http://google-styleguide.googlecode.com/svn/trunk/javaguide.html)
* Chapter 5 : Formatting, in _Clean Code - A Handbook of Agile Software Craftsmanship_ - [On Amazon](http://www.amazon.fr/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
