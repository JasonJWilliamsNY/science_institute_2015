#Quiz III Review Sheet

### Quiz Topics

### Sanger Sequencing
Be able to define and explain the following:

* Sequencing primers-A primer is a short nucleic acid sequence that provides a starting point for DNA synthesis, here it provides when in the DNA sequnece the DNA sequencing should start
* Dideoxynucleotides- ddNTP is added to a reaction as a chain-elongating inhibititor of DNA Polymerase. Dideoxynucleotides are missing 2 nucleotides and also have a floursecent dye <br> by adding the ddNTP the DNA sequence will not contiune binding and will terminate leaving us now with many stand on DNA ending in different colors at different loci <br> we therefore can now put if together and since each color stands for a different base we and ends at diiferent point can find DNA sequence
* Steps in sequencing process (melting, annealing, polymerase function)- during the melting stage the DNA is heated up, denatures and the double strands are separtated. Next comes the annealing stage where the reaction is cooled long enough for the PCR Primer to bond to the single strand DNA. During the extension stage, the nucleotides float around randomly and if the correct one hits the polymerase, it gets attached. Instead of dNTP being incorporated a ddNTP will be incorporated but the ddNTP prevents the matching nucleotide from attaching because it doesn't fit, thus causing the chain to terminate. 
* Purpose of electrophoresis in polyacrylamide gel- polyacrylamid gel is much thicker and gives us a much higher resolution than agorose gel. The machine separates the strands by size/weight and in polyacrylamide it is very detailed. 

See: [Sequencing animation](https://www.dnalc.org/resources/animations/cycseq.html)
[Explained sequencing very well](https://seqcore.brcf.med.umich.edu/doc/dnaseq/primers.html)
### Data Analysis

Be able to explain:

* What is the purpose of trimming DNA sequencing reads (why must you do this?) <br> it is often difficult to get the sequencing for the start and end of DNA barcode so by trimming off the ends we are unsure about have greater chance of finding correct matches
* &nbsp;&nbsp;&nbsp; DNA Sequencers usually produce poor quality sequences with missing nucleotides at the start and end of the sequence. Trimming removes misleading data that is incorrect, mostly in the beginning and end of a sequence.
* What the BLAST tool does:
* &nbsp;&nbsp;&nbsp; This tool allows us to search for similar DNA Sequences. It uses an algorithm to search GenBank (large collection of DNA Sequences) to find sequences that have similar barcode and most likley match up with sequence we have.
* What is a transition, transversion (mutation types)
 &nbsp;&nbsp;&nbsp; Transition: a mutation where a purine and purine or a peremidine and peremidine attach, which involves bases of similar shape. 
 &nbsp;&nbsp;&nbsp; Transversion: a mutation where a peremidine and purine attach, which involves an exchange of one-ring and two-ring structures
 &nbsp;&nbsp;&nbsp; Transition mutations are more likely to happen than transversions because substituting a single ring structure for another single ring structure is more common than substituting a double ring for a single ring structure. 

### Your Contribution to these topics (Sequencing)
Sequencing is when we try to find the DNA sequence or barcode of a given section of DNA. We use the primer to signify where the Barcooding starts. After the primer attaches the bases start attaching untill at random a ddNTP attaches therefore terminating the chain. The ddNTP is a cetain color depending on base after do this many times have many strands all end  in 1/4 colors at different loci. We then use polyacrylamide gel to order the DNA in size as specific as one hbase apart.Using a lazer can  tell which color showing which base. Then putting together the base number and what base it is able to find DNA sequence.

### Your Contribution to these topics (Data Analysis)
We use blasting to analize our sequence data- the Algorithm then searches GenBank to see if there are any other sequences that have a similar barcode to the one found

### Your suggested quiz questions (due by 12/27)

1. Why would one use command-line as opposed to point-and-click in scientific computing? it can be more specific and less likley to miss click it also ha the ability to replicate things very quickly which can be a major advantage in sceince. 
2. What's so special about polyacrylamide gel? <br> it hads very high resolution seperating stands up to one base apart
3.Why is it more likley for there to be a transition rahter than a transvertion? <br>Transition mutations are more likely to happen than transversions because substituting a single ring structure for another single ring structure is more common than substituting a double ring for a single ring structure.
4.Why is it important for scientist to contribute to GenBank? <br> when science contribute to GenBank they're dicoveries can ehlp others make even more dicoveries. It really show the message of science and the importance and value of working with one another to help us move farther in dicoveries (look at this cite for more info)[http://www.ncbi.nlm.nih.gov/pmc/articles/PMC165504/] 
