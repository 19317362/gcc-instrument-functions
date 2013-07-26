gcc-instrument-functions
========================

**compile:**

>     gcc -finstrument-functions foo.c



**then run the executable.**


test
----

compile `00gcc -finstrument-functions foo.c`

>     1gcc -finstrument-functions foo.c


>     2gcc -finstrument-functions foo.c
>>     3gcc -finstrument-functions foo.c

>>    4gcc -finstrument-functions foo.c

    5gcc -finstrument-functions foo.c
> `6gcc -finstrument-functions foo.c`

`7gcc -finstrument-functions foo.c`


