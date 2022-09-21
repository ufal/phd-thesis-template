# phd-thesis-template
A template PhD thesis at UFAL

Compile with:

```
cd thesis
lualatex thesis
bibtex thesis
makeglossaries thesis
lualatex thesis
lualatex thesis
```
... and don't forget to download fresh ACL anthology:

```
wget https://aclanthology.org/anthology.bib.gz
pigz -d anthology.bib.gz
```

(see https://zlib.net/pigz/)
