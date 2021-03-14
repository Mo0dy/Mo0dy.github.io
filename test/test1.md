
# Table of Contents

1.  [This is some description of some intersting code](#org8236529)
    1.  [Overview](#org090d864)
    2.  [Example Usage](#org8bdac3a)
    3.  [Thorough usage documentation](#org21add34)
    4.  [Documentation](#orgf3d21ad)
        1.  [Dependencies](#orgc460193)
        2.  [This one difficult function](#org19c396a)



<a id="org8236529"></a>

# This is some description of some intersting code


<a id="org090d864"></a>

## Overview

This does something


<a id="org8bdac3a"></a>

## Example Usage

    python my_test_script.py -i somedata


<a id="org21add34"></a>

## Thorough usage documentation

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<tbody>
<tr>
<td class="org-left">-m</td>
<td class="org-left">filename of input data</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">-i</td>
<td class="org-left">output file name</td>
<td class="org-left">optional</td>
</tr>
</tbody>
</table>


<a id="orgf3d21ad"></a>

## Documentation


<a id="orgc460193"></a>

### Dependencies

This module soley depends on numpy.

    import numpy as np


<a id="org19c396a"></a>

### This one difficult function

this function adds two numbers

    def do_something_complicated(a : int, b : int) -> int:
        return a + b

