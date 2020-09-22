# Streaming Analysis
Applying Streaming methods using Pyspark and counting the number of inbound packets in terms of the attack type in each DStream

# About the data set 
The raw network packets of the UNSW-NB151 dataset was created by the IXIA PerfectStorm tool in the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS) for generating a hybrid of real modern normal activities and synthetic contemporary attack behaviours. Tcpdump tool used to capture 100 GB of the raw traffic (e.g., Pcap files). This data set has nine types of attacks, namely, Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode and Worms. The Argus and Bro-IDS tools are used and twelve algorithms are developed to generate totally 49 features with the class label
