12.How would you reverse a string? 

This is my simple code in JS which is reversing given string

for(var I = 0; i < (str.length/2);i++)

       {
              var temp  = str[i];
              str[i] = str[str.length-1-i];
              str[str.length-1-i] = temp;

       }

