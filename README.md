# CubiLang
CubLang, I made a VERY annoying programming language

# Vscode Syntax

This comes with a VSCODE syntax, no compiler however...

# How to use.

I'm just going to dump the commands here, I don't care about you.

cub=if|whl|forWhen|System|prntout|floating|ISflase|IStrue|glbl|lib|graphics.cubil|merry.cubl|node.cubl|output.cubl|global|closed|public|class|hidden|graphics.create|graphics.destroy|graphics.text|unoutput|IO|READ|WRITE|file|=|add|sub|dest|deleteint|==|--|!!!|int|bool|float|numb|define|data|v|

# Hello World Example (yikes)

```
lib{
    output.cubl
}

global{
    READ(v)
}

hidden{
    class{
        define{
            'Helloworld.class'
        }
        data{
            'Hello World!'
        }
        cub=if{
            bool, On == IStrue{
                prntout(data^^)
            }
        }
    }
}

numb{
    define{
        'On', 'Off'
    }
    int 1
    int 0
    {define bool}
}
```

# How the Hello World example works.

1. Imports output.cubl (a cubl is like a .h file.)
2. Reads global, nothing is there, that would end the program so we need to go down and read 'hidden' by going down with v (down 1, if you wanted 2 you could do vv, and so on)
3. Create a hidden class, so that it only prints once, create a class and defines the name.
4. Adds the data, the text that it will print.
5. Adds a if statement, using the On varible we define later in the code. It then prints the data thats up ^^ (2)
6. Defines On and Off. If Off, it will display error, we need these to create the if statement in the first place.
