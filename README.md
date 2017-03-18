# Automate_kSNP

Added new parameter "-e" or "--extension" to **kSNPv3automate.py**. This enables the script to recognize genome assembly FASTA file extensions of your choice. Original script only detected files with a *.fasta* extension. 

For genome assembly FASTA files ending with *.fna*
```bash

python kSNPv3automate.py -p /directory/of/input/fasta/files -k 21 -e fna -o /directory/of/kSNP3/output/files

```

For genome assembly FASTA files ending with *.fa*
```bash

python kSNPv3automate.py -p /directory/of/input/fasta/files -k 21 -e fa -o /directory/of/kSNP3/output/files

```
