## [TABLEM3](https://help.hexagonmi.com/bundle/MSC_Nastran_2022.4/page/Nastran_Combined_Book/qrg/bulktuv/TOC.TABLEM3.xhtml) - Material Property Table, Form 3

Defines a tabular function for use in generating temperature-dependent material properties.  Also contains parametric data for use with the table.

#### Format:

```nastran
$---1---$---2---$---3---$---4---$---5---$---6---$---7---$---8---$---9---$---10--$
TABLEM3 TID     X1      X2                                              +       
+       x1      y1      x2      y2      x3      y3      -etc.-                  
```

#### Example:

```nastran
$---1---$---2---$---3---$---4---$---5---$---6---$---7---$---8---$---9---$---10--$
TABLEM3 62      126.9   30.0                                            +       
+       2.9     2.9     3.6     4.7     5.2     5.7     ENDT                    
```

```text
┌───────────┬──────────────────────────────────────────────────────────────────────────┐
│ Describer │ Meaning                                                                  │
├───────────┼──────────────────────────────────────────────────────────────────────────┤
│ TID       │ Table identification number.  See Remark 7. (Integer > 0 or Integer < 0) │
├───────────┼──────────────────────────────────────────────────────────────────────────┤
│ X1, X2    │ Table parameters.  See Remark 6. (Real; X20.0)                           │
├───────────┼──────────────────────────────────────────────────────────────────────────┤
│ xi, yi    │ Tabular values.  (Real)                                                  │
└───────────┴──────────────────────────────────────────────────────────────────────────┘
```