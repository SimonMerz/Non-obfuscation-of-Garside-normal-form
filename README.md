# Non obfuscating power of Garside normal forms
This project contains the necessary parts of WalnutDSA^TM and our universal forgery attack on it implemented in MAGMA. Moreover, it contains our decomposition algorithm to solve some instances of the conjugacy search problem in braid groups.

The necessary parts of WalnutDSA^TM to generate signatures can be found in Walnut.txt. Our attack on the signature scheme is implemented in Attack.txt as well as a function to verify whether our universal forgery attack was successful. 
Test.txt can be used to generate a given number of WalnutDSA^TM instances, apply the attack on it and check whether we launched a successful universal forgery attack.

Conjugacysearch.txt contains a function applying the same decomposition algorithm used to forge Walnut signatures to solve instances of the conjugacy search problem in braid groups.  The success of the algorithm can be tested using TestCSP on randomly generated instances of CSPs in braid groups (given the number of strands N and the length of the braid words). 
