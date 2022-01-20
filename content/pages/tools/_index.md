---
content_type: page
title: Tools
uid: aaf4057a-bac7-5b9e-89ac-ae095a684679
---

[Scheme software](http://www.gnu.org/software/mit-scheme/) is required to run the .scm files in this section. The .ini and .edwin files in this section are customization files that can be loaded into Edwin, the [MIT Scheme](http://www.gnu.org/software/mit-scheme/index.html) text editor.

Scheme Substitution Model
-------------------------

Notes on the Scheme Substitution Model ([PDF]({{< baseurl >}}/resources/submodel))

_Pattern Matching Code_
-----------------------

*   match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm)) Procedures for pattern matching with "context variables," as explained at the beginning of the file.
*   eliza.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/eliza.scm)) Procedures for a minimal "doctor" dialog program based on pattern matching. Illustrates use of "tilde" variables that match any number of items in a list; does not use context variables. Load "match.scm" before evaluating this file.
*   deriv-simplify-rules.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/derivsimplifyrules.scm)) Procedures for simplifying arithmetic expressions with simple derivatives, as explained at the beginning of the file. Load "match.scm" before evaluating this file.

Scheme Substitution Model
-------------------------

*   sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/sm.scm)) A Scheme Substitution Model interpreter based on pattern-matching rewrite rules. This file begins with a brief intro to the Scheme Substitution Model, along with further instructions for running the interpreter. Use a Loader file to load the interpreter.
*   Loader files for the Interpreter (choose one):
    *   mitscheme-loadsm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/mitschemeloadsm.scm)): To run the Scheme Substitution Model interpreter described in sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/sm.scm)) using MIT Scheme, evaluate this load-file in a directory containing match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm)) and sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/sm.scm)). (Make sure your Edwin/Emacs \*scheme\* buffer also has this directory as its working directory, (see (pwd) and (cd "filename") in the MIT Scheme references)
    *   drscheme-loadsm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/drschemeloadsm.scm)): To run the Scheme Substitution Model interpreter described in sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/sm.scm) ) using Rice U. DrScheme, evaluate this load-file in a directory containing match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm)) and sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/sm.scm))
    *   other-loadsm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/otherloadsm.scm) ): To run the Scheme "Substitution Model" interpreter described in sm.scm using a Scheme implementation other than MIT Scheme or DrScheme, FILL IN THE BLANKS in this load-file as appropriate to the implementation, and then evaluate this load-file in a directory containing match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm)) and sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/sm.scm))  
          
         
*   test-submodel.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/testsubmodel.scm)), politician.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/politician.scm)): Sample expressions to evaluate in the Substitution Model.
*   Submodel with parallel convergence operator CNVG? cnvg-loadsm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/cnvgloadsm.scm)), cnvg-sm.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/cnvgsm.scm))  
     

### Scheme Information

*   The online Scheme repository is [available](http://www.schemers.org/). In particular, the latest official Scheme specification is in the [Revised^5 Report on the Algorithmic Language Scheme](http://www.schemers.org/Documents/Standards/R5RS/HTML/), also available in PDF format ([PDF](http://www.schemers.org/Documents/Standards/R5RS/r5rs.pdf)).
*   [Introductory Scheme Texts]({{< baseurl >}}/pages/tools/some_scheme-based_introductory_programming_texts)
*   Sample edwin customization file for Unix ([EDWIN](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/Unnamed.edwin)) and Windows ([INI](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/edwin.ini))