# s3
Smart Shell Script (s3) is a collection of shell scripts developed by myself and other platform engineers to enhance the efficiency of system administration tasks.


# `fcd` - Fast cd

I have built up this script based on the qcd (Quick cd) script from Daniel Barrett, from the book _Efficient Linux at the Command Line_ [^1].

I just tried to separate my favorite directories from the script. By default, they will be placed in ~/.fcdpaths.cfg.
</br>

### Installation

Just put the script in your script folder in the system, create an alias (for better efficiency), set the permissions to allow execution, and add your first path and name it:

```shell
"qux /foo/bar/" >> ~/.fcdpaths.cfg
# qux - pathname
# /foo/bar/ - existent path
```

</br>

### Usage

```shell
fcd qux
```
</br>
</br>
</br>

---

[^1]: Efficient Linux at the Command Line by Daniel J. Barrett (O’Reilly). Copyright 2022 Daniel Barrett, 978-1-098-11340-7.