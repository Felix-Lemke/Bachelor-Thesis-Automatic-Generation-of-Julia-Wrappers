# Bachelor-Thesis-Automatic-Generation-of-Julia-Wrappers

Usage Guide:
To get started you need to have a julia installation
first you need the PythonCall.jl package. You can add it by typing
```
add PythonCall
```
in the PackageManager of the Julia REPL

next you need to the close the Package Manager but stay in the Repl and type
```
using PythonCall
```
now you reenter the Package Manager and type 

```
conda add numpy
```
replace numpy with the library you want to generate the wrapper for

now change the rootmodule of PythoncallSkript to the module you want to wrap.
now a File should get generated that wraps you module that you can include in other files like you would any other
