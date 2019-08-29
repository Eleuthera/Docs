### E_IDENT


#### 32 Bit
|Alias     |Offset | Description          |
|----------|-------|----------------------|
|EI_MAG0   |0      |Magic                 |
|EI_MAG1   |1      |Magic 'E'             |
|EI_MAG2   |2      |Magic 'L'             |
|EI_MAG3   |3      |Magic 'F'             |
|EI_CLASS  |4      |File class            |
|EI_DATA   |5      |Data encoding         |
|EI_VERSION|6      |File version          |
|EI_PAD    |7      |Start of padding bytes|

#### 64 Bit
|Alias        |Offset | Description          |
|-------------|-------|----------------------|
|EI_MAG0      |0      |Magic                 |
|EI_MAG1      |1      |Magic 'E'             |
|EI_MAG2      |2      |Magic 'L'             |
|EI_MAG3      |3      |Magic 'F'             |
|EI_CLASS     |4      |File class            |
|EI_DATA      |5      |Data encoding         |
|EI_VERSION   |6      |File version          |
|EI_OSABI     |7      |ABI                   |
|EI_ABIVERSION|8      |ABI Version           |
|EI_PAD       |9      |Start of padding bytes|

