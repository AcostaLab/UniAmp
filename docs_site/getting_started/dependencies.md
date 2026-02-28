# Dependencies

UniAmp is run on Linux and requires basic Linux utilities, python3, and perl.<br>
<br>
UniAmp contains wrappers around public bioinformatics software. The following dependencies are included with UniAmp as binaries in the `bin` folder and do not need to be installed:<br>
- [nucmer](https://sourceforge.net/projects/mummer/) <br>
- [bedtools](https://github.com/arq5x/bedtools2) <br>
- [bioawk](https://github.com/lh3/bioawk) <br>
- [usearch](https://drive5.com/usearch/download.html) <br>
- [blastn](https://www.ncbi.nlm.nih.gov/books/NBK52640/) <br>
- [taxonkit](https://github.com/shenwei356/taxonkit) <br>
- [datasets](https://www.ncbi.nlm.nih.gov/datasets) <br>
- [RNAmmer](https://services.healthtech.dtu.dk/service.php?RNAmmer-1.2)\*<br>
- [edirect](https://www.ncbi.nlm.nih.gov/books/NBK179288/)<br>

\* To implement `rnammer` in UniAmp scripts, the `rnammer` script included with UniAmp was modified as described [here](https://www.biostars.org/p/9550142/). `rnammer` also requires the HMMER2 command `hmmsearch`, so the binary for this command is included in the UniAmp `bin` folder.<br>
<br>
\* `rnammer` requires the perl `XML::Simple` module. If not already installed, the module can be installed using the command `cpan install XML::Simple`. 
