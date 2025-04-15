# CBT535
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 535 is from Deru Sudibyo and contains CCAT, which is a    *   FILE 535
//*           TSO command for dynamic dataset allocation,           *   FILE 535
//*           dataset concatenation, and deconcatenation.           *   FILE 535
//*                                                                 *   FILE 535
//*           CCAT is more flexible, and can do more things,        *   FILE 535
//*           than most programs of this type.                      *   FILE 535
//*                                                                 *   FILE 535
//*           email:   deru.sudibyo@gmail.com                       *   FILE 535
//*                                                                 *   FILE 535
//*           As an alternative, try:                               *   FILE 535
//*                                                                 *   FILE 535
//*           email:  sbgolob@cbttape.org                           *   FILE 535
//*                                                                 *   FILE 535
//*           See new member $$NOTE01 from Sam Golob.               *   FILE 535
//*                                                                 *   FILE 535
//*   SYNTAX:                                                       *   FILE 535
//*                                                                 *   FILE 535
//*   (1)   Perform allocation/deallocation:                        *   FILE 535
//*                                          +-   -+ +-     -+      *   FILE 535
//*         CCAT  F(ddname) DS(datasetname)  | ON  | | MSG   |      *   FILE 535
//*                                          |     | |       |      *   FILE 535
//*                                          | top | | nomsg |      *   FILE 535
//*                                          |     | |       |      *   FILE 535
//*                                          | bot | | emsg  |      *   FILE 535
//*                                          |     | |       |      *   FILE 535
//*                                          | off | | lmsg  |      *   FILE 535
//*                                          +-   -+ +-     -+      *   FILE 535
//*                                                                 *   FILE 535
//*        Option 1.    ON    -   Allocate/concatenate the          *   FILE 535
//*                               specified DSname/DDname.  If      *   FILE 535
//*                               the DDname is already exist,      *   FILE 535
//*                               dataset will be concatenated      *   FILE 535
//*                               on the top of concatenation.      *   FILE 535
//*                                                                 *   FILE 535
//*                     TOP   -   Force to concatenate a dataset    *   FILE 535
//*                               to the top order of existing      *   FILE 535
//*                               concatenation.  If specified      *   FILE 535
//*                               dataset is newly added, this      *   FILE 535
//*                               option is default.                *   FILE 535
//*                                                                 *   FILE 535
//*                     BOT   -   Force to concatenate a dataset    *   FILE 535
//*                               to the bottom order of existing   *   FILE 535
//*                               concatenation.                    *   FILE 535
//*                                                                 *   FILE 535
//*                     OFF   -   Deallocate/deconcatenate the      *   FILE 535
//*                               specified DSname/DDname.          *   FILE 535
//*                                                                 *   FILE 535
//*        Option 2.    MSG   -   Display simple message (default)  *   FILE 535
//*                                                                 *   FILE 535
//*                     NOMSG -   No messages will be displayed     *   FILE 535
//*                               upon completion.                  *   FILE 535
//*                                                                 *   FILE 535
//*                     EMSG  -   Display error messages only.      *   FILE 535
//*                                                                 *   FILE 535
//*                     LMSG  -   Display complete messages         *   FILE 535
//*                               (completion message and the       *   FILE 535
//*                               new concatenation list).          *   FILE 535
//*                                                                 *   FILE 535
//*                                                                 *   FILE 535
//*   (2)   Display current specified DDname concatenation list:    *   FILE 535
//*                                                                 *   FILE 535
//*         CCAT  F(ddname)                                         *   FILE 535
//*                                                                 *   FILE 535
```
