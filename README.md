# Fibonacci-series
In this html code you will be able to get the answer of the entered input of fibonacci sequence
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>  
        // declaration of the variables  
        var n1 = 0,  n2 = 1, next_num, i;  
        var num = parseInt (prompt (" Enter the limit for Fibonacci Series "));  
        document.write( "Fibonacci Series: ");  
        for ( i = 1; i <= num; i++)  
        {  document.write (" <br> " +  n1); // print the n1  
            next_num = n1 + n2; // sum of n1 and n2 into the next_num  
              
            n1 = n2; // assign the n2 value into n2  
            n2 = next_num; // assign the next_num into n2  
        }  
          
        </script> 

    
</body>
</html>
