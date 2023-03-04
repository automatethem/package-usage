# package-usage

Correct usage
<pre>
import mymodulea

import mypackagea
mypackagea.mymodulea

import my_module_a

import my_package_a
my_package_a.my_module_a
</pre>

Incorrect usage (runtime error)
<pre>
#import my-module-a #SyntaxError: invalid syntax

#import my-package-a #import package-a
#my-package-a.my-module-a
</pre>

https://wikidocs.net/135472
