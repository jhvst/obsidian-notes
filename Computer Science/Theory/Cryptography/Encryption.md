## Homomorphic encryption

Probably the most interesting encryption area of this century.

IBM: https://www.ibm.com/blogs/research/2020/06/ibm-releases-fully-homomorphic-encryption-toolkit-for-macos-and-ios-linux-and-android-coming-soon/ [[2020]]

Light reading from [[Vitalik Buterin]]: https://vitalik.ca/general/2020/07/20/homomorphic.html 

And a link from that article to matrix-based FHE: How to Run [[Turing Machine]]s on Encrypted Data https://eprint.iacr.org/2013/229.pdf [[2013]] [[Homomorphic encryption]] 

Fully Homomorphic Encryption Part One: A Gentle Intro http://blog.higashi.tech/2020/06/16/fhe_01.html

 ... has implications for [[sandboxing]] methods, e.g. Google has “confidential computing” https://cloud.google.com/confidential-computing for use-cases in which the customer wants to ensure that if the virtualization hypervisor has a security flaw, then the VM neighbors on that physical machine cannot inspect the data on other machines. more description https://www.usenix.org/system/files/sec19-li-mengyuan_0.pdf (edited) 

however, in this scheme, Google (or AMD or whatever) can still backdoor the VMs because the hypervisor assigns the encryption keys to the VMs. with homomorphic encryption, models and data can be encrypted before remote computation, thus there is a much stronger guarantee that the data cannot be inspected by any party.