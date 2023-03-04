# package-usage

Correct usage
<pre>
import mymodulea

import mypackagea
mypackagea.mymodulea

import mypackagea
mypackagea.mymoduleb
</pre>
<pre>
import my_module_a

import my_package_a
my_package_a.my_module_a

import my_package_a
my_package_a.my_module_b
</pre>

Incorrect usage (runtime error)
<pre>
import my-module-a #SyntaxError: invalid syntax

import my-package-a #SyntaxError: invalid syntax
my-package-a.my-module-a

import my-package-a #SyntaxError: invalid syntax
my-package-a.my-module-b
</pre>
