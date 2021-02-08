# Magentron\MetaphoneSpanish\MetaphoneSpanish  

The Spanish Metaphone Algorithm (Algoritmo del Metáfono para el Español)

This script implements the Metaphone algorithm (c) 1990 by Lawrence Philips.
It was inspired by the English double metaphone algorithm implementation by
Andrew Collins - January 12, 2007 who claims no rights to this work
(http://www.atomodo.com/code/double-metaphone)

The metaphone port adapted to the Spanish Language is authored
by Alejandro Mosquera <amosquera@dlsi.ua.es> November, 2011
(https://github.com/amsqr/Spanish-Metaphone) and is covered
under this copyright:

Copyright 2011, Alejandro Mosquera <amosquera@dlsi.ua.es>.  All rights reserved.

This metaphone port adapted to the Spanish Language for PHP is authored
by Jeroen Derks <jeroen@derks.it> December, 2018
(https://github.com/Magentron/Spanish-Metaphone-PHP) and is covered
under this copyright:

Copyright 2018, Jeroen Derks <jeroen@derks.it>.  All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice, this
list of conditions and the following disclaimer in the documentation and/or
other materials provided with the distribution.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.  





## Methods

| Name | Description |
|------|-------------|
|[metaphone](#metaphonespanishmetaphone)|Calculate the metaphone key of a Spanish string.|




### MetaphoneSpanish::metaphone  

**Description**

```php
public metaphone (string $string, int $phonemes)
```

Calculate the metaphone key of a Spanish string. 

 

**Parameters**

* `(string) $string`
: The input string.  
* `(int) $phonemes`
: This parameter restricts the returned metaphone key to phonemes characters in length.  
The default value of 0 means no restriction.  

**Return Values**

`string`

> The metaphone key as a string, if successfully calculated;  
False, otherwise.


<hr />

