# HUGO-STATIC - Blogging in a dynamic static world

> What man is a man who does not make the world better.
>
> -- Balian, Kingdom of Heaven

## Abstract
This is a helm chart to create a pod containing a static web page generate by Hugo extended.

## License
The license for the software is LGPL 3.0 or newer. 


## Architecture

tl;dr (ok, only the bullshit bingo words):
- Immutable Objects
- Relying heavily on generated code
- 100 % test coverage of human generated code
- Every line of code not written is bug free!

Code test coverage for human generated code should be 100%, machinge generated code is considered bugfree until proven 
wrong. But every line that needs not be written is a bug free line without need to test it. So aim for not writing code.


## A note from the author
I'm working on another project that can be found on github [(HUGO-STATIC)](https://github.com/KaiserpfalzEDV/hugo-static). And while
developing that piece of software I ran on the blocker not being able to nicely handle OIDC UMA. I looked around and
found no library to abstract away UMA from my code. So I decided to write one.

If someone is interested in getting it faster, we may team up. I'm open for that. But be warned: I want to do it 
_right_. So no short cuts to get faster. And be prepared for some basic discussions about the architecture or software 
design :-).

---
Bensheim, 2022-12-05
