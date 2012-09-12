# htmlDec
converts html special entities back to plain text

the conversation table is taken from
http://www.w3schools.com/tags/ref_entities.asp
http://www.w3schools.com/tags/ref_symbols.asp

##example
    var htmlDec = require('htmlDec');

    var input = '&quot; &lt; T E X T &gt; &quot;';
    var decoded = htmlDec(input);
    console.log(decoded) // prints " < T E X T > "
