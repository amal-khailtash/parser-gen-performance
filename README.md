# parser-gen-performance
Performance numbers for different parser generators.  

The [grammar on this page](http://www.dalkescientific.com/writings/diary/archive/2007/11/03/antlr_java.html) was used to create and compare various parser generators:

```
                        Time (s)       Relative
------------------------------------------------
Lex/Yacc     (C)      :  0.004569292 -    1.000
re           (Python) :  0.044694662 -    9.782
ANTLR4       (Java)   :  0.127022912 -   27.799
PLY          (Cython) :  0.300076008 -   65.672
PLY          (Python) :  0.430262327 -   92.404
SLY          (Python) :  0.534606695 -  117.000
PyBison      (Python) :  0.486946583 -  106.569
Lark         (Python) :  0.662305117 -  144.947
Parsimonious (Python) :  0.788778067 -  172.626
PyParsing    (Python) :  1.674643040 -  366.499
ANTLR4       (Python) :  4.481964350 -  980.888
Grako        (Python) : 10.759706497 - 2354.786
```

## References
* [flex/yacc](http://dinosaur.compilertools.net/)
* [ANTLR](www.antlr.org)
* [PLY](https://github.com/dabeaz/ply)
* [SLY](https://github.com/dabeaz/sly)
* [PyBison](https://github.com/smvv/pybison)
* [Lark](https://github.com/lark-parser/lark)
* [Parsimonious](https://github.com/erikrose/parsimonious)
* [PyParsing](https://github.com/pyparsing/pyparsing)
* [Grako](https://github.com/swayf/grako)
