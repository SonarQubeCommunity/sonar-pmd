# ClassCastExceptionWithToArray
**Category:** `pmd`<br/>
**Rule Key:** `pmd:ClassCastExceptionWithToArray`<br/>


-----

if you need to get an array of a class from your Collection, you should pass an array of the desidered class as the parameter of the toArray method. Otherwise you will get a ClassCastException.
