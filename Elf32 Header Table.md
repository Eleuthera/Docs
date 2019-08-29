
### Elf32 Header Table

|size |Label      |Brief Description                |
|-----|-----------|---------------------------------|
|4    |e_ident    |Magic codes                      |
|2    |e_machine  |Self explanatory                 |
|4    |e_version  |Never 0                          |
|4    |e_entry    |Entry point for the program      |
|4    |e_phoff    |Program header offset            |
|4    |e_shoff    |Section header offset            |
|4    |e_flags    |I don't even know                |
|2    |e_ehsize   |Elf header size                  |
|2    |e_phentsize|Program header entry size        |
|2    |e_phnum    |Program header number            |
|2    |e_shentsize|Section header entry size        |
|2    |e_shnum    |Section header number            |
|2    |e_shstrndx |Section header string table index|
