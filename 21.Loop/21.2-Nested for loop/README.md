Nested for loop
---------------
For loop inside for loop
Syntax:
    for(initialization; test-condition; increment or decrement)
        {   
            block of statements;
            for(initialization; test-condition; increment or decrement)
                {
                    block of statements;
                }
        }

    for(i=0; i<3; i++)
        {   
            document.write(i);
            for(j=0; j<5; j++)
                {
                    document.write(j);
                }
        }