## Purpose

This package helps to manage space padding around paired delimiters.

    E.g. {a=>1, b=>2}
          ^
          <SPC>
         { a=>1, b=>2 }
           ^
          <DEL>
         {a=>1, b=>2}

I made it to conform to some coding standards, but I actually haven't found
an instance where I wanted to add an uneven spacing inside delimiters; so
it's a global minor-mode that I just leave enabled now.  
