# GtkSourceView-snippets-and-lang-specs
GNOME's source viewer (Gedit and Builder) has code snippets plugin and builtin syntax highlighting specification but some are somewhat incomplete or lacking.  
I know for python there is Gedi (Jedi) for autocompletion but I found that fidly to get working and I would rather no boxes pop-up over my work as I'm typing.

## Python 3 Code Snippets
There are no code snippets for python 3 in Gedit there are a dozen Python 2 code snippets which can be transfered and they can work, so you don't need this

### Minimum Goals
 - [ ] Implementing Python [full grammer](https://docs.python.org/3/reference/grammar.html) through nested snippets
 - [ ] Built-in function's snippet that `try's` to evaluate the values you put into the function if not provides comment with helpful info
 - [x] Authoring snippet to add a header that makes [this](http://web.archive.org/web/20111010053227/http://jaynes.colorado.edu/PythonGuidelines.html)
 - [ ] Maybe som more features (please suggest)
 - [x] Fast Comprehensions lists and dict 
 - [x] Fast selected text insertions to string, list, set
 - [x] Binary Sequence Generator
 - [ ] I have one `macro`? called clamp that inserts a max and min nest maybe some more functions of that type

### Future Goals
 - [ ] Built-in Constant where f goes to False and t goes to True on tab and so on
 - [ ] Built-in Type functions e.g. ". means string ]. means list and so forth
 - [ ] Built-in Exceptions at minimum you can Write lowercase and get Camel-ed cased Exceptions
 - [ ] Importable functions pre-packaged with python can be also be snippeted?

## HTML Code Snippets
I have had a look at it, I'm not a web developer but I think it's handy if you can see all the attributes available to you in html context only.  Meaning don't put in attributes that can be set/changed from CSS as that is what CSS is for.  Also expand to every HTML5 tag instead of purly relying on div's and the id attribute.

### Minimum Goals
 - [ ] HTML tag snippets
 - [ ] Complete tag attributes
 - [ ] Authoring snippets
 - [ ] Welcome to further suggestions

## Python 3 Syntax Language Specification
This lacks in a few areas but the first one that comes to mind is python's literal formating strings the `{variable}` area should be a different colour to the rest of the string.  Not really important but when doing binary, octal or hex representations with `0b`, `0o` and `0x` those prefix should also have a different style to rest of the `number`.  Furthermore with dictionaries if you have a string for both key and value then the key string should be styled differently to assist readability.
  Built-in functions, types and classes get syntax highlighting why can user defined ones also get this?  It might be a limintation of the spec but if not I will implement that.  

================

#### More to come

