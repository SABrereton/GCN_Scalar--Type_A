
# GCN Scalar - Type A


### About this document / Introduction

The purpose of this document is to provide some information about
GCN Scalar - Type A.


### About GCN Scalar - Type A

GCN Scalar - Type A is a puzzle game where an image file is divided up
into pieces which are then shuffled and the player has to reassemble
the image by rearranging the shuffled pieces.

GCN Scalar - Type A is a fork from version 1.02 of "Scalar" by Milan
Babuskov.

Version 1.02 of "Scalar" was obtained from the program's project
repository hosted at the web-based project hosting service provider
SourceForge (https://sourceforge.net/ at the time of writing).

The "Type A" designation in this case means that this fork shall use
the same flat two dimensional graphical interface as the original
"Scalar" program.

The purpose of the "GCN" prefix is to help distinguish it from the
original program and other possible versions/forks.


### Implementations

Implementations are forks of GCN Scalar - Type A. The idea behind this scheme is to provide flexibility to attempt to “implement” the same general concept using different development methods.

The implementations that have currently been released are as follows:

- Imp00001 - [ Target platform(s): Microsoft Windows on 32bit x86 compatible systems ]
    
    The purpose of this implementation is to predominantly use the C
    and/or C++ programming languages along with the Simple DirectMedia
    Layer (SDL) 1.2.X API to develop versions of GCN Scalar - Type A
    that will run on systems that use versions of the Microsoft Windows
    operating system that run on 32bit x86 compatible system architecture.

    To run the program you will need to obtain copies of the required .dll library files.
    I have made a collection of various SDL 1.2.X and SDL 1.2.X extention .dll library files which should include those required by this implemenatation.
    The collection can by downloaded from it's own repository [Here]( https://github.com/SABrereton/GCN_File_Collection--SDL_1.2.X_for_MS_Windows_32bit_x86).
    
    - Downloads & Changelog

        [Changelog]( /Changelogs/GCN_Scalar-tA-Imp00001-Changelog.txt)\
        [Version 1 - The Program]( https://github.com/SABrereton/GCN_Scalar--Type_A/releases/download/Imp00001-Version_1-The_program/GCN_Scalar-tA-Imp00001-v0p1--Prg.zip)\
        [Version 1 - The Source Code]( https://github.com/SABrereton/GCN_Scalar--Type_A/releases/download/Imp00001-Version_1-The_source_code/GCN_Scalar-tA-Imp00001-v0p1--Src.zip)

    - Images

        [Version 1 - Running on Microsoft Windows 10 Home](/Images/imp00001-v1--capture01.png "Version 1 of implementation Imp00001")

    - Additional content

        Image files can be added to or removed from the "images" folder if you
        wish to change the images that you play with. The image file formats
        .bmp, .jpeg and .png are supported aswell as others that are supported
        by the SDL_image library.

        I have made collections of additional images available at the links below.

        [Additional images 01]( https://github.com/SABrereton/GCN_Scalar--Type_A/releases/download/Additional_images_01/Additional_Images_01.zip )\
        [Additional images 02]( https://github.com/SABrereton/GCN_Scalar--Type_A/releases/download/Additional_images_02/Additional_Images_02.zip )   


### Legal / Licencing Information

Scalar is licenced under the GNU General Public License version 2.0 (GPLv2)
and thus GCN Scalar - Type A is also licenced under GNU General Public
License version 2.0 (GPLv2).
