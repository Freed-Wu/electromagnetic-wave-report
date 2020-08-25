electromagnetic-wave-report
===========================

A backup of my homework.

[电磁场与电磁波实验指导说明书](doc/电磁场与电磁波实验指导说明书.pdf)

Dependent
---------

1.  A LaTex distribution. Such as [texlive].
2. [cnlogo]: provide Chinese university logos. Include the logo of Nanjing
    University of Science and Technology.

Install
-------

``` {.zsh}
git clone git@github.com:Freed-Wu/electromagnetic-wave-report
cd electromagnetic-wave-report
latexmk -pvc main.tex
```

Q & A
-----

More question see [Issues].

If you don't wanna compile, you can download the complied paper from
[Release]

  [texlive]: https://github.com/TeX-Live/texlive-source
  [cnlogo]: https://github.com/yuxtech/cnlogo
  [Issues]: https://github.com/Freed-Wu/electromagnetic-wave-report/issues
  [Release]: https://github.com/Freed-Wu/electromagnetic-wave-report/releases/

