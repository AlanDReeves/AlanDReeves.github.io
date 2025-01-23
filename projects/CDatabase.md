---
layout: project
type: project
image: img/databaseSquare.png
title: "C/C++ Database"
date: 2024
published: true
labels:
  - C
  - C++
  - Databases
summary: "A database implemented in both C and C++ which I made for my Program Structure class"
---

This project was a database which I created in both a C and C++ version. Both versions operated on a textual interface through the terminal for the front end with a linked list handling the majority of the back end. While the backend was the main focus of this project, the text interface ended up more complicated than I originally expected. One challenge of the text interface was that it was required to accept not only the whole name of the menu option the user requested, but also any input which was a substring of the menu option's name. One of the functions of these programs was that it would read an existing file and continue to update it, so that the database file could theoretically be passed as a copy. It was also all run off of a Unix server owned by the university. 

Below is a capture of what the text interface looks like.
 
<img class="img-fluid" src="../img/c++TextSnip.png">

The following is an exerpt from my C++ code:
```cpp
int llist::findRecord(int acctNum)
{
    int returnVal = -1;
    struct record* cursor = start;

    #ifdef DEBUGMODE
    cout << "called findRecord(int " << acctNum << ")" << endl;
    #endif

    if (start == NULL)
    {
        returnVal = -1;
    }
    else
    {
        while ((*cursor).next != NULL && acctNum != (*cursor).accountno)
        {
            #ifdef DEUGMODE
            cout << "executed loop\n";
            #endif
            
            cursor = (*cursor).next;
        }
        if (((*cursor).accountno == acctNum))
        {
            cout << (*cursor).accountno;
            cout << endl;
            cout << (*cursor).name;
            cout << (*cursor).address;
            cout << endl;

            returnVal = 0;
        }
    }
    return returnVal;
}
```

In this project I gained a much greater understanding of both C and C++, as well as the use of pointers. It also served as a great way to compare the design of object oriented code vs sequential progamming. The C++ version of the code was of course designed much differently, even though it was based on the C version, which I created first. 

There were no teams for this project, so all of the work was done by me.
