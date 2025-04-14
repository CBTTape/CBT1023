# CBT1023
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE1023 is from Richard Humphris, and contains a package of   *   FILE1023
//*           programs to produce a Cross-Reference report for      *   FILE1023
//*           REXX programs, which is very useful.  The programs    *   FILE1023
//*           are referred to, as the REXX xreference utility.      *   FILE1023
//*                                                                 *   FILE1023
//*     email:  richard.humphris <richard.humphris@netnitco.net>    *   FILE1023
//*                                                                 *   FILE1023
//*     Revised:    10/21/2023                                      *   FILE1023
//*                                                                 *   FILE1023
//*     DESCRIPTIVE OVERVIEW OF XREFERENCE...                       *   FILE1023
//*                                                                 *   FILE1023
//*     Why do we need/want a REXX xref?   Because variables        *   FILE1023
//*     are not declared in REXX, and any misspelling of a          *   FILE1023
//*     variable (in an assignment and/or reference) can easily     *   FILE1023
//*     go undetected.   But with an xref and using it in           *   FILE1023
//*     looking for problems (especially in large execs), is        *   FILE1023
//*     much easier than visually looking thru an entire rexx       *   FILE1023
//*     exec.                                                       *   FILE1023
//*                                                                 *   FILE1023
//*     And the IBM rexx compiler, which not every one has, has     *   FILE1023
//*                only recently added the following support in     *   FILE1023
//*                their xreference: XREF has been enhanced to      *   FILE1023
//*                provide more details in the compiler             *   FILE1023
//*                listing, such as information about exposed       *   FILE1023
//*                and dropped variables, variables without         *   FILE1023
//*                assignment, and optimization stoppers.           *   FILE1023
//*                                                                 *   FILE1023
//*     This, free offering, on the CBT tape, does almost           *   FILE1023
//*            everything the IBM compiler does.   But it also      *   FILE1023
//*            provides more visual clues than the IBM compiler     *   FILE1023
//*            has.   This XREF has: - provides references for      *   FILE1023
//*            exposed and dropped variables (just like it does     *   FILE1023
//*            for any other reference).  - variables in the        *   FILE1023
//*            xreference are separated by:                         *   FILE1023
//*                  - assignment use                               *   FILE1023
//*                  - reference use                                *   FILE1023
//*                  - label definition (and warns about            *   FILE1023
//*                  duplicate labels) - label use (function,       *   FILE1023
//*                  call, signal on, call on) - variable shows     *   FILE1023
//*                  up in xref in either UPPER or Lower case       *   FILE1023
//*                  (upper case, if never assigned a value)        *   FILE1023
//*            - stem variables show up in the xref along with      *   FILE1023
//*                  any variables used after the first period.     *   FILE1023
//*                  - any assignment/reference to a stem           *   FILE1023
//*                  variable also appears with any variables       *   FILE1023
//*                  used after the stem.                           *   FILE1023
//*                  - and those variables to the right of the      *   FILE1023
//*                  stem will appear in either UPPER or LOWER      *   FILE1023
//*                  case depending on whether that variable        *   FILE1023
//*                  was ever assigned a value.   Note:   IBM's     *   FILE1023
//*                  compiler also shows variables used with a      *   FILE1023
//*                  stem variable, but doesn't show (visually)     *   FILE1023
//*                  whether variable was assigned a value (or      *   FILE1023
//*                  not)).                                         *   FILE1023
//*                                                                 *   FILE1023
//*     Like the IBM compiler XREF, close examination of the        *   FILE1023
//*     XREF can help you identify problems with the rexx code      *   FILE1023
//*     that would be hard to spot otherwise.   Hopefully, the      *   FILE1023
//*     upper/lower case in this xreference may make it even        *   FILE1023
//*     easier to use than a normal xref.                           *   FILE1023
//*                                                                 *   FILE1023
//*     IBM's compiler also creates a xref for literals.   This     *   FILE1023
//*     one does not.   If this is a feature you want, please       *   FILE1023
//*     contact me and I may provide that as well.                  *   FILE1023
//*                                                                 *   FILE1023
//*     Included in the the offering is extensive                   *   FILE1023
//*     documentation, along with sample rexx exec's (and their     *   FILE1023
//*     associated xreference output).                              *   FILE1023
//*                                                                 *   FILE1023
//*     Also the documentation, using sample rexx execs and         *   FILE1023
//*     xref listings, shows various problems that can be           *   FILE1023
//*     detected in the xref.                                       *   FILE1023
//*                                                                 *   FILE1023
//*     In addition, the documentation provides some technical      *   FILE1023
//*     information about how the rexx xref itself works            *   FILE1023
//*     internally.   Along with some rexx performance tips in      *   FILE1023
//*     the technical documentation.                                *   FILE1023
//*                                                                 *   FILE1023
```
