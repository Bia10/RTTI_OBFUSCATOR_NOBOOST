# C++ RTTI Obfuscator
Obfuscates all RTTI (Run-time type information) inside a binary so AC's can't catch you on it.

Credits to https://github.com/koemeet/rtti-obfuscator!
I've just got rid of the annoying boost dependencies. :-)

### Usage
You can simply drop any binary into it and it outputs the obfuscated binary in `<relative-dir>/<filename>.tan.<extension>`.

It can also be used on the command line by simply providing the path to the input binary as its first argument:
```
$ rtti-obfuscator <path-to-binary>
```

### Preview

RTTI (left pane) | Obfuscated RTTI (right pane)
![](http://i.imgur.com/DdhjIsv.jpg)

This is how a binary would look without any RTTI obfuscation:
![](https://i.imgur.com/GDWNMNY.png)

Now when ran through the obfuscator, it will turn into this:
![](https://i.imgur.com/02MnMbm.png)
