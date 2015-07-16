-------- PROJECT GENERATOR --------
PROJECT NAME :	test3
PROJECT DIRECTORY :	W:\ASP-WORK\SSP-LESSEN\test3\test3
CPU SERIES :	RX600
CPU TYPE :	RX62N
TOOLCHAIN NAME :	Renesas RX Standard Toolchain
TOOLCHAIN VERSION :	1.2.1.0
GENERATION FILES :
    W:\ASP-WORK\SSP-LESSEN\test3\test3\dbsct.c
        Setting of B,R Section
    W:\ASP-WORK\SSP-LESSEN\test3\test3\typedefine.h
        Aliases of Integer Type
    W:\ASP-WORK\SSP-LESSEN\test3\test3\lowlvl.src
        Program of Low level
    W:\ASP-WORK\SSP-LESSEN\test3\test3\lowsrc.c
        Program of I/O Stream
    W:\ASP-WORK\SSP-LESSEN\test3\test3\sbrk.c
        Program of sbrk
    W:\ASP-WORK\SSP-LESSEN\test3\test3\iodefine.h
        Definition of I/O Register
    W:\ASP-WORK\SSP-LESSEN\test3\test3\intprg.c
        Interrupt Program
    W:\ASP-WORK\SSP-LESSEN\test3\test3\vecttbl.c
        Initialize of Vector Table
    W:\ASP-WORK\SSP-LESSEN\test3\test3\vect.h
        Definition of Vector
    W:\ASP-WORK\SSP-LESSEN\test3\test3\resetprg.c
        Reset Program
    W:\ASP-WORK\SSP-LESSEN\test3\test3\test3.c
        Main Program
    W:\ASP-WORK\SSP-LESSEN\test3\test3\lowsrc.h
        Header file of I/O Stream file
    W:\ASP-WORK\SSP-LESSEN\test3\test3\sbrk.h
        Header file of sbrk file
    W:\ASP-WORK\SSP-LESSEN\test3\test3\stacksct.h
        Setting of Stack area
START ADDRESS OF SECTION :
 H'1000	B_1,R_1,B_2,R_2,B,R,SU,SI
 H'FFFF8000	PResetPRG
 H'FFFF8100	C_1,C_2,C,C$*,D_1,D_2,D,P,PIntPRG,W*,L
 H'FFFFFFD0	FIXEDVECT

* When the user program is executed,
* the interrupt mask has been masked.
* 
* Program start 0xFFFF8000.
* RAM start 0x1000.

SELECT TARGET :
    RX600 Simulator
DATE & TIME : 2014/06/25 17:04:42
