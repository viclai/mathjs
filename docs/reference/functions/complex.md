# Function complex

Create a complex value or convert a value to a complex value.

The method accepts the following arguments:     complex()                           creates a complex value with zero                                         as real and imaginary part.     complex(re : number, im : string)   creates a complex value with provided                                         values for real and imaginary part.     complex(re : number)                creates a complex value with provided                                         real value and zero imaginary part.     complex(complex : Complex)          clones the provided complex value.     complex(arg : string)               parses a string into a complex value.     complex(array : Array)              converts the elements of the array                                         or matrix element wise into a                                         complex value.     complex({re: number, im: number})   creates a complex value with provided                                         values for real an imaginary part.     complex({r: number, phi: number})   creates a complex value with provided                                         polar coordinates

Example usage:     var a = math.complex(3, -4);     // 3 - 4i     a.re = 5;                        // a = 5 - 4i     var i = a.im;                    // -4;     var b = math.complex('2 + 6i');  // 2 + 6i     var c = math.complex();          // 0 + 0i     var d = math.add(a, b);          // 5 + 2i


### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`args` | * &#124; Array &#124; Matrix | 

### Returns

Type | Description
---- | -----------
Complex &#124; Array &#124; Matrix | value




<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->