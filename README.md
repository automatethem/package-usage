# package-usage

<pre>
import modulea

import packagea
#packagea.modulea #AttributeError: module 'packagea' has no attribute 'modulea'

import module_a

import package_a
#package_a.module_a #AttributeError: module 'package_a' has no attribute 'module_a'

#import module-a #SyntaxError: invalid syntax

#import package-a #import package-a
#package-a.module-a
</pre>

https://wikidocs.net/135472
