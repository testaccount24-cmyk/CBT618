# CBT618
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 618 is from Pergentino Arias and contains a package of    *   FILE 618
//*           programs to encrypt and decrypt your data using       *   FILE 618
//*           IBM's ICSF Cryptographic Services Facility.           *   FILE 618
//*                                                                 *   FILE 618
//*           email:  "Pergentino Arias" <pergen@mixmail.com>       *   FILE 618
//*                                                                 *   FILE 618
//*        -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -        *   FILE 618
//*                                                                 *   FILE 618
//*     Package Description:                                        *   FILE 618
//*                                                                 *   FILE 618
//*     Here is a little application that calls the                 *   FILE 618
//*     CRYPTOGRAPHIC ICSF API'S.                                   *   FILE 618
//*                                                                 *   FILE 618
//*     All the programs are in REXX.                               *   FILE 618
//*                                                                 *   FILE 618
//*     You need access to keys and to the ICSF.                    *   FILE 618
//*                                                                 *   FILE 618
//*     The programs are in xmit format in member XEXEC.            *   FILE 618
//*     The panels are in xmit format in member XPLIB.              *   FILE 618
//*     The messages are in xmit format in member XMLIB.            *   FILE 618
//*                                                                 *   FILE 618
//*     You only have to start with the REXX PCSF and follow        *   FILE 618
//*     the panels.                                                 *   FILE 618
//*                                                                 *   FILE 618
//*     Note: You have to put your CKDS and your PKDS in            *   FILE 618
//*           program PCSF and all the application works with       *   FILE 618
//*           your files.                                           *   FILE 618
//*                                                                 *   FILE 618
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - -     *   FILE 618
//*                                                                 *   FILE 618
//*     In addition to this, there are other programs too.          *   FILE 618
//*                                                                 *   FILE 618
//*        In order to create asymetric keys, I put several         *   FILE 618
//*        keys RSA in the members:                                 *   FILE 618
//*                   RSA11024                                      *   FILE 618
//*                   RSA1512  ---> see this first                  *   FILE 618
//*                   RSA21024                                      *   FILE 618
//*                   RSA31024                                      *   FILE 618
//*                   RSA41024                                      *   FILE 618
//*                   RSA51024                                      *   FILE 618
//*                   RSA61024                                      *   FILE 618
//*                   RSA71024                                      *   FILE 618
//*                   RSA81024                                      *   FILE 618
//*                   RSA91024                                      *   FILE 618
//*        This keys are in assembler format for use with a         *   FILE 618
//*        program that put them in the PKDS.  You can use          *   FILE 618
//*        program RSACREA changing the member that use to put      *   FILE 618
//*        the key in the PKDS, and the key label, which is         *   FILE 618
//*        RSAPRU.                                                  *   FILE 618
//*                                                                 *   FILE 618
//*        Other programs                                           *   FILE 618
//*                                                                 *   FILE 618
//*        1   Generate random numbers                              *   FILE 618
//*            COBOL example: randomc                               *   FILE 618
//*            ASML example:  randoma                               *   FILE 618
//*                                                                 *   FILE 618
//*        2   Create symmetric keys using API   KEY GENERATE       *   FILE 618
//*            The program in COBOL:   DESCRECB                     *   FILE 618
//*            The program in ASM:     DESCREAS                     *   FILE 618
//*            With the JCL:           CREASIM                      *   FILE 618
//*                                                                 *   FILE 618
//*        3   Create symetric keys using RANDOM GENERATOR and      *   FILE 618
//*            IMPORT                                               *   FILE 618
//*            The program in COBOL:   DESRANCB                     *   FILE 618
//*            The program in ASM:     DESRANAS                     *   FILE 618
//*                                                                 *   FILE 618
//*        4   Signatures                                           *   FILE 618
//*            5.1    RSADSS1 creates the key RSADSS for            *   FILE 618
//*                   signatures.                                   *   FILE 618
//*                   RSADSS2 makes a signature from a text and     *   FILE 618
//*                   verifies it.                                  *   FILE 618
//*                                                                 *   FILE 618
//*     You can compile all the Assembler programs using the        *   FILE 618
//*     proc ASMCOMP.                                               *   FILE 618
//*     You can compile all the COBOL programs using the proc       *   FILE 618
//*     COBCOMP.                                                    *   FILE 618
//*                                                                 *   FILE 618
```
