
### Elf64 Header Table

|size |Label      |Brief Description                |
|-----|-----------|---------------------------------|
|16   |e_ident    |Magic codes                      |
|2    |e_type     |Object file type                 |
|2    |e_machine  |Self explanatory                 |
|4    |e_version  |Never 0                          |
|8    |e_entry    |Entry point for the program      |
|8    |e_phoff    |Program header offset            |
|8    |e_shoff    |Section header offset            |
|4    |e_flags    |I don't even know                |
|2    |e_ehsize   |Elf header size                  |
|2    |e_phentsize|Program header entry size        |
|2    |e_phnum    |Program header number            |
|2    |e_shentsize|Section header entry size        |
|2    |e_shnum    |Section header number            |
|2    |e_shstrndx |Section header string table index|

<br>

<br>

Okay, so there's also a file for each of these labels. 
In the file should be some stuff relating to what values these labels take.
