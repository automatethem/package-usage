# package-usage

<pre>
import mymodulea

import mypackagea
#mypackagea.mymodulea #AttributeError: module 'packagea' has no attribute 'modulea'

import my_module_a

import my_package_a
#my_package_a.my_module_a #AttributeError: module 'package_a' has no attribute 'module_a'

#import my-module-a #SyntaxError: invalid syntax

#import my-package-a #import package-a
#my-package-a.my-module-a
</pre>

https://wikidocs.net/135472
