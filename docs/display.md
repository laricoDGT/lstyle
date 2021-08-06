# Display Variants

### For responsive

add `sm, md, lg, xl or xxl` with colon `:` before to class name for example:

```bash
<div class="dn md:db xl:df"></div>
```

## display

| Class Name | Properties             |
| ---------- | ---------------------- |
| .dn        | display: none;         |
| .db        | display: block;        |
| .dib       | display: inline-block; |
| .dt        | display: table;        |
| .di        | display: inherit;      |
| .df        | display: flex;         |
| .dif       | display: inline-flex;  |
| .dg        | display: grid;         |

## flex-wrap

| Class Name | Properties               |
| ---------- | ------------------------ |
| .fww       | flex-wrap: wrap;         |
| .fwn       | flex-wrap: nowrap;       |
| .fwwr      | flex-wrap: wrap-reverse; |

## flex-direction

| Class Name | Properties                      |
| ---------- | ------------------------------- |
| .fdr       | flex-direction: row;            |
| .fdrr      | flex-direction: row-reverse;    |
| .fdc       | flex-direction: column;         |
| .fdcr      | flex-direction: column-reverse; |

## justify-content

| Class Name | Properties                      |
| ---------- | ------------------------------- |
| .jcfs      | justify-content: flex-start;    |
| .jcc       | justify-content: center;        |
| .jcfe      | justify-content: flex-end;      |
| .jcsb      | justify-content: space-between; |
| .jcsa      | justify-content: space-around;  |
| .jcse      | justify-content: space-evenly;  |

## align-content

| Class Name | Properties                    |
| ---------- | ----------------------------- |
| .acfs      | align-content: flex-start;    |
| .acc       | align-content: center;        |
| .acfe      | align-content: flex-end;      |
| .acsb      | align-content: space-between; |
| .acsa      | align-content: space-around;  |

## align-self

| Class Name | Properties              |
| ---------- | ----------------------- |
| .asa       | align-self: auto;       |
| .asfs      | align-self: flex-start; |
| .asc       | align-self: center;     |
| .asfe      | align-self: flex-end;   |
| .ass       | align-self: stretch;    |

## align-items

| Class Name | Properties               |
| ---------- | ------------------------ |
| .aic       | align-items: center;     |
| .ais       | align-items: flex-start; |
| .aie       | align-items: flex-end;   |
| .aib       | align-items: baseline;   |
| .ais       | align-items: stretch;    |

## flex

| Class Name | Properties      |
| ---------- | --------------- |
| .f01a      | flex: 0 1 auto; |
| .f110      | flex: 1 1 0%;   |
| .f11a      | flex: 1 1 auto; |
| .fn        | flex: none;     |

## flex-grow

| Class Name | Properties    |
| ---------- | ------------- |
| .fg1       | flex-grow: 1; |
| .fg0       | flex-grow: 0; |

## flex-shrink

| Class Name | Properties      |
| ---------- | --------------- |
| .fs1       | flex-shrink: 1; |
| .fs0       | flex-shrink: 0; |

## order

| Class Name | Properties    |
| ---------- | ------------- |
| .o0        | order: 0;     |
| .o1        | order: 1;     |
| .o2        | order: 2;     |
| .o3        | order: 3;     |
| ...        | ...           |
| .o11       | order: 11;    |
| .o12       | order: 12;    |
|            |               |
| .ofirst    | order: -9999; |
| .olast     | order: 9999;  |

## gap

The font-size CSS property sets the size of the font.

**Values** → 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48;

_Font size converted "px" to → "rem"_

| Class Name | Properties    |
| ---------- | ------------- |
| .g4        | gap: 0.25rem; |
| .g8        | gap: 0.5rem;  |
| .g12       | gap: 0.75rem; |
| .g16       | gap: 1rem;    |
| .g20       | gap: 1.25rem; |
| .g24       | gap: 1.5rem;  |
| .g28       | gap: 1.75rem; |
| .g32       | gap: 2rem;    |
| .g36       | gap: 2.25rem; |
| .g40       | gap: 2.5rem;  |
| .g44       | gap: 2.75rem; |
| .g48       | gap: 3rem;    |

## row-gap

| Class Name | Properties        |
| ---------- | ----------------- |
| .rg4       | row-gap: 0.25rem; |
| .rg8       | row-gap: 0.5rem;  |
| .rg12      | row-gap: 0.75rem; |
| .rg16      | row-gap: 1rem;    |
| .rg20      | row-gap: 1.25rem; |
| .rg24      | row-gap: 1.5rem;  |
| .rg28      | row-gap: 1.75rem; |
| .rg32      | row-gap: 2rem;    |
| .rg36      | row-gap: 2.25rem; |
| .rg40      | row-gap: 2.5rem;  |
| .rg44      | row-gap: 2.75rem; |
| .rg48      | row-gap: 3rem;    |

## column-gap

| Class Name | Properties           |
| ---------- | -------------------- |
| .cg4       | column-gap: 0.25rem; |
| .cg8       | column-gap: 0.5rem;  |
| .cg12      | column-gap: 0.75rem; |
| .cg16      | column-gap: 1rem;    |
| .cg20      | column-gap: 1.25rem; |
| .cg24      | column-gap: 1.5rem;  |
| .cg28      | column-gap: 1.75rem; |
| .cg32      | column-gap: 2rem;    |
| .cg36      | column-gap: 2.25rem; |
| .cg40      | column-gap: 2.5rem;  |
| .cg44      | column-gap: 2.75rem; |
| .cg48      | column-gap: 3rem;    |

## column-count

The CSS multi-column layout allows easy definition of multiple columns of text - just like in newspaper

**Values** → 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12;

| Class Name | Properties                  |
| ---------- | --------------------------- |
| .cc1       | column-count: 1;            |
| .cc2       | column-count: 2;            |
| .cc3       | column-count: 3;            |
| ...        | ...                         |
| .cc11      | column-count: 11;           |
| .cc12      | column-count: 12;           |
|            |                             |
| .bia       | break-inside: avoid-column; |
| .caa       | column-span: all;           |

## grid-template-columns

| Class Name | Properties                                         |
| ---------- | -------------------------------------------------- |
| .gtc1      | grid-template-columns: repeat(1, minmax(0, 1fr));  |
| .gtc1      | grid-template-columns: repeat(2, minmax(0, 1fr));  |
| .gtc3      | grid-template-columns: repeat(3, minmax(0, 1fr));  |
| ...        | ...                                                |
| .gtc11     | grid-template-columns: repeat(11, minmax(0, 1fr)); |
| .gtc12     | grid-template-columns: repeat(12, minmax(0, 1fr)); |
|            |                                                    |
| .gtcn      | grid-template-columns: none;                       |

## grid-template-rows

| Class Name | Properties                                      |
| ---------- | ----------------------------------------------- |
| .gtr1      | grid-template-rows: repeat(1, minmax(0, 1fr));  |
| .gtr1      | grid-template-rows: repeat(2, minmax(0, 1fr));  |
| .gtr3      | grid-template-rows: repeat(3, minmax(0, 1fr));  |
| ...        | ...                                             |
| .gtr11     | grid-template-rows: repeat(11, minmax(0, 1fr)); |
| .gtr12     | grid-template-rows: repeat(12, minmax(0, 1fr)); |
|            |                                                 |
| .gtrn      | grid-template-rows: none;                       |

## grid-column

| Class Name | Properties                    |
| ---------- | ----------------------------- |
| .gc1       | grid-column: span 1/span 1;   |
| .gc2       | grid-column: span 2/span 2;   |
| .gc3       | grid-column: span 3/span 3;   |
| ...        | ...                           |
| .gc11      | grid-column: span 11/span 11; |
| .gc12      | grid-column: span 12/span 12; |
|            |                               |
| .gca       | grid-column: auto;            |

## grid-column-start

| Class Name | Properties               |
| ---------- | ------------------------ |
| .gcs1      | grid-column-start: 1;    |
| .gcs2      | grid-column-start: 2;    |
| .gcs3      | grid-column-start: 3;    |
| ...        | ...                      |
| .gcs11     | grid-column-start: 11;   |
| .gcs12     | grid-column-start: 12;   |
|            |                          |
| .gcsa      | grid-column-start: auto; |

## grid-column-end

| Class Name | Properties             |
| ---------- | ---------------------- |
| .gce1      | grid-column-end: 1;    |
| .gce2      | grid-column-end: 2;    |
| .gce3      | grid-column-end: 3;    |
| ...        | ...                    |
| .gce11     | grid-column-end: 11;   |
| .gce12     | grid-column-end: 12;   |
|            |                        |
| .gcea      | grid-column-end: auto; |

## grid-row

| Class Name | Properties                 |
| ---------- | -------------------------- |
| .gr1       | grid-row: span 1/span 1;   |
| .gr2       | grid-row: span 2/span 2;   |
| .gr3       | grid-row: span 3/span 3;   |
| ...        | ...                        |
| .gr11      | grid-row: span 11/span 11; |
| .gr12      | grid-row: span 12/span 12; |
|            |                            |
| .gra       | grid-row: auto;            |

## rid-row-start

| Class Name | Properties            |
| ---------- | --------------------- |
| .grs1      | grid-row-start: 1;    |
| .grs2      | grid-row-start: 2;    |
| .grs3      | grid-row-start: 3;    |
| ...        | ...                   |
| .grs11     | grid-row-start: 11;   |
| .grs12     | grid-row-start: 12;   |
|            |                       |
| .grsa      | grid-row-start: auto; |

## grid-row-end

| Class Name | Properties          |
| ---------- | ------------------- |
| .gre1      | grid-row-end: 1;    |
| .gre2      | grid-row-end: 2;    |
| .gre3      | grid-row-end: 3;    |
| ...        | ...                 |
| .gre11     | grid-row-end: 11;   |
| .gre12     | grid-row-end: 12;   |
|            |                     |
| .grea      | grid-row-end: auto; |

## grid-auto-flow

| Class Name | Properties                    |
| ---------- | ----------------------------- |
| .gafr      | grid-auto-flow: row;          |
| .gafc      | grid-auto-flow: column;       |
| .gafrd     | grid-auto-flow: row dense;    |
| .gafcd     | grid-auto-flow: column dense; |
