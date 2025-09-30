---
content_type: page
description: ''
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: aaf4057a-bac7-5b9e-89ac-ae095a684679
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{% resource_link "fde6d96a-2a54-4ce0-a4d3-6f3eb3319399" "Scheme software" %}} is required to run the .scm files in this section. The .ini and .edwin files in this section are customization files that can be loaded into Edwin, the {{% resource_link "9ff5e5e9-a10d-4694-a1a7-cd0efb1a6e1d" "MIT Scheme" %}} text editor.

Scheme Substitution Model
-------------------------

Notes on the Scheme Substitution Model ({{% resource_link 02d60bb7-4e90-93dd-658b-55d6bd421f94 "PDF" %}})

_Pattern Matching Code_
-----------------------

*   match.scm ({{% resource_link 8112d601-8e07-f3f6-2390-a92f1b8247f2 "SCM" %}}) Procedures for pattern matching with "context variables," as explained at the beginning of the file.
*   eliza.scm ({{% resource_link e5fb8383-7714-1496-fa9e-0e706c527a4a "SCM" %}}) Procedures for a minimal "doctor" dialog program based on pattern matching. Illustrates use of "tilde" variables that match any number of items in a list; does not use context variables. Load "match.scm" before evaluating this file.
*   deriv-simplify-rules.scm ({{% resource_link 4a1e7f30-a984-947c-c81d-a0db872d9543 "SCM" %}}) Procedures for simplifying arithmetic expressions with simple derivatives, as explained at the beginning of the file. Load "match.scm" before evaluating this file.

Scheme Substitution Model
-------------------------

*   sm.scm ({{% resource_link 94b08770-d013-cf7e-ea8c-7c8788e84d24 "SCM" %}}) A Scheme Substitution Model interpreter based on pattern-matching rewrite rules. This file begins with a brief intro to the Scheme Substitution Model, along with further instructions for running the interpreter. Use a Loader file to load the interpreter.
*   Loader files for the Interpreter (choose one):
    *   mitscheme-loadsm.scm ({{% resource_link 7c53f8f5-5713-6bc0-9f34-224d6defb9c2 "SCM" %}}): To run the Scheme Substitution Model interpreter described in sm.scm ({{% resource_link 94b08770-d013-cf7e-ea8c-7c8788e84d24 "SCM" %}}) using MIT Scheme, evaluate this load-file in a directory containing match.scm ({{% resource_link 8112d601-8e07-f3f6-2390-a92f1b8247f2 "SCM" %}}) and sm.scm ({{% resource_link 94b08770-d013-cf7e-ea8c-7c8788e84d24 "SCM" %}}). (Make sure your Edwin/Emacs \*scheme\* buffer also has this directory as its working directory, (see (pwd) and (cd "filename") in the MIT Scheme references)
    *   drscheme-loadsm.scm ({{% resource_link 8d3e5928-c5b1-2bab-91c2-f9cc01f94ad1 "SCM" %}}): To run the Scheme Substitution Model interpreter described in sm.scm ({{% resource_link 94b08770-d013-cf7e-ea8c-7c8788e84d24 "SCM" %}} ) using Rice U. DrScheme, evaluate this load-file in a directory containing match.scm ({{% resource_link 8112d601-8e07-f3f6-2390-a92f1b8247f2 "SCM" %}}) and sm.scm ({{% resource_link 94b08770-d013-cf7e-ea8c-7c8788e84d24 "SCM" %}})
    *   other-loadsm.scm ({{% resource_link d64e7a2e-428c-0c03-7731-1c3d77113713 "SCM" %}} ): To run the Scheme "Substitution Model" interpreter described in sm.scm using a Scheme implementation other than MIT Scheme or DrScheme, FILL IN THE BLANKS in this load-file as appropriate to the implementation, and then evaluate this load-file in a directory containing match.scm ({{% resource_link 8112d601-8e07-f3f6-2390-a92f1b8247f2 "SCM" %}}) and sm.scm ({{% resource_link 94b08770-d013-cf7e-ea8c-7c8788e84d24 "SCM" %}})  
          
         
*   test-submodel.scm ({{% resource_link 3b862539-b20d-7db5-311e-54ae9c449fb7 "SCM" %}}), politician.scm ({{% resource_link b61e97e7-49ad-d33f-3195-caea76adc59f "SCM" %}}): Sample expressions to evaluate in the Substitution Model.
*   Submodel with parallel convergence operator CNVG? cnvg-loadsm.scm ({{% resource_link 3b5903b8-943f-eabc-826e-42c7eca1859a "SCM" %}}), cnvg-sm.scm ({{% resource_link 96f48080-62fb-70ac-4577-a488d4b38df8 "SCM" %}})  
     

### Scheme Information

*   The online Scheme repository is {{% resource_link "7eef1722-1cb3-4fc6-9fa8-3de3c3017e0c" "available" %}}. In particular, the latest official Scheme specification is in the {{% resource_link "d84e561d-6f48-497a-80b4-99655372d8b4" "Revised^5 Report on the Algorithmic Language Scheme" %}}, also available in PDF format ({{% resource_link "76bd000b-c05c-4eda-810a-29b9511d0039" "PDF" %}}).
*   {{% resource_link 80ec84f3-9be5-b835-b90c-5780aa8f823f "Introductory Scheme Texts" %}}
*   Sample edwin customization file for Unix ({{% resource_link 581f6f0f-7445-4749-056f-b9f637c0b3ff "EDWIN" %}}) and Windows ({{% resource_link 721a9873-1615-54a6-dd43-0d485a65be7a "INI" %}})