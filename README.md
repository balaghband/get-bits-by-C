# get-bits-by-C
This C program reads records from the standard input stream, * passes the data in each valid record to * getbits and displays the result. it receives three inputs  * x, p and n and the program displays the result after this operation * if there will be no error:  (x >> (p+1-n)) &amp; ~(~0 &lt;&lt; n) * The result of this operation is the numbero of getbits.
