ontab
=====
auto complete logic 

usage
=====
```
var ot = new OnTab( function( value ) {
      console.log( value ); 
    } );

ot.context = [ 'apple', 'hello', 'ass' ]; 
ot.autoComplete( 'a' ); 
ot.autoComplete( 'a' );
```

printout: 
>
apple  
ass
