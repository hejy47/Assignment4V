# Assignment4V: A Dataset of Buggy Verilog Programming Assignments

This dataset is constructed from Verilog programming assignments of an online undergraduate course. We have received the exemption and obtained consent from the students writing the assignments in our dataset.

## Main statistics

| Project | Description | # Defects | LOC | TBLOC |
| :------ | :---------- | :-------: | :-: | :---: |
| counter6bit | 6-bit decimal counter | 23 | 63 | 49 |
| decl7s | 7 segment display decoder | 2 | 31 | 32 |
| decoder3e | 38 decoder | 5 | 11 | 35 |
| fa_behavioral | Full adder | 5 | 12 | 35 |
| JG3 | Three judge circuit | 14 | 24 | 33 |
| latch24 | 24-bit register | 4 | 14 | 52 |
| mux21 | 21 multiplexer | 4 | 13 | 34 |
| Total | - | 57 | 168 | 270 |

## Directory Overview

```
Assignment4V/
|-dataset/
|--Assignment4V.conf
|--Assignment4V/
|---counter6bit/
|----counter6bit_1/
|-----diff.log
|-----buggy/
|------counter6bit_test.v
|------counter6bit_tb.v
|------test.txt
|------test.vcd
|-----fix/
|---...
|-README.md
```

The folder `dataset` contains the assignment programs:

* `buggy` -- the source folder of buggy version.
* `fixed` -- the source folder of fixed version.
* `diff.log` -- the diff text between buggy version and fixed version.