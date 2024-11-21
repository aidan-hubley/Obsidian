---What is a an Image?
- A virtually sound copy of a system, RAM, etc. 

--- What goes in a Report?
- Executive Summary, Timeline, Evidence, Conclusion

--- What are the 3 steps of computer forensics? <>
1. Collect 
2. Analyze 
3. Present 

-- What is the difference between Digital forensics and Computer forensics? <>
- Computer forensics is a subset of Digital forensics, because Digital forensics can include cameras

--- What are 2 challenges in regards to computer forensics? <>
- (Data) Privacy
- Encryption
	- One thing to collect data, another to be able to decrypt encryption

--- What are the 2 constitutional amendments that are applicable cybersecurity?<>
- fourth amendment (protection against unreasonable search and seizure)
- fifth amendment (protection against self-incrimination)

--- What are the types of computer forensics? <>
1. Database forensics
2. Email forensics
3. Malware forensics
4. Memory forensics
5. Mobile forensics
6. Network forensics

---  What is CISA? <>
- Cybersecurity and Infrastructure Agency

--- When was CISA created? <>
- 2019

--- What is the goal of forensics?
- To present evidence to the court

--- What are the two methodologies of data collection? <>
- live box
- dead box

--- What takes long to acquire? <>
- Live box, there are processes running, it takes longer

--- What are the two data types potentially collect?
- Persistent
- Volatile

--- What is Persistent data?
- Data stored on a hard drive

--- Where does volatile data reside? <>
- Registry
- Caches
- Random Access Memory (RAM)

--- What is volatile data? <>
- Data in transit 

--- What is the name of your system?
- Run WinAudit, check in 'System Overview'

--- What are the 2 types of Image formats? <>
1. DD (raw, no metadata)
2. E01 (broke into segments, has metadata)

--- What is the difference between a Raw (DD file) and E01? <>
- Raw (DD) doesn't have metadata and is a single huge chuck
- EO1 has metadata and is in segments

--- What does a writeblocker do? <>
- Protects / prevents you from writing to the source file and from the source file writing to you

--- What are the 2 types of writeblockers? <>
- Software
- Hardware

--- What is the order of volatility? <>
1. registers, cache
2. routing table, ARP cache, process table, kernel statistics, memory
3. temporary file systems
4. disk
5. remote logging and monitoring data that is relevant to the system in question
6. physical configuration, network topology
7. archival media

-- Does the order of volatility goes from less to more, or more to less? <>
- More volatile to less volatile

--- 