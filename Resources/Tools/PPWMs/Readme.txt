PPWMs


PPWMs is a tool for predicting palmitoylation sites based on protein sequence. The program is implemented in C. The win32 console version is provided.



1. Input File

The input file is in the FASTA format. Each file can includes one or multiple sequences. Each sequence must have the amino acid "C". More sequences require more computer resource. For typical computer, the number of sequences less than 50 should be fine.

The output will be saved into "Result.txt" in the same directory.


2. Command Line

  PPWMS  <Input File> <Cutoff>

where  <Input File> is specified above.

 The Cutoff should be "Low", "Medium" and  "High" correspoding  to differernt true positive rates respectively. 

For examle:
  PPWMs   P49802.fasta  Low


3. Contacts

Any question or advice please email to dengnaiyang@vip.163.com or liyx0723@163.com.
