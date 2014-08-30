Digital Clock:

    Clock with format HH MM SS ( not implemented yet)
    Format  HH changeable between 0 - 12 and 0-24  ( AM-PM Led not implemented )

Description:

    Cicuit uses two  4 bit counters, 74191 .  They dont have reset pin but preload.  so the logical combination can trig that
    load (00)  to restart the counting.  the switch allows to have the modulo 24 or the modulo 12 counting and BCD formatting
    

TO DO:

    * complete the rest of the counter.
    * Add a programmable alarm
    * change the switch with a switchbutton.
    
Best Regards

    Julio Alexander Aguilar Angulo
    juloaguilar@gmail.com
