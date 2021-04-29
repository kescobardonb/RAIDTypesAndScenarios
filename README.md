# RAIDTypesAndScenarios

Project title:  A definitive explanation of RAID types and its use case scenarios
This will be a definitive explanation of RAID types, its different pros and cons and scenarios which it best used for.

Team members/position:
> Karl Escobar - leader
> JC Viray - member
> Sofia Lopez - rapporteur

Brief Description: RAID is a type storage configuration that have several benefits for whatever use case scenario you may have. Here in this repository we will take a dive of whatRAID is and several type of RAIDs that can be used to improve performance or security of data transfer and storage.

Resources:
#https://www.steadfast.net/blog/almost-everything-you-need-know-about-raid
#https://www.youtube.com/watch?v=U-OCdTeZLac&ab_channel=PowerCertAnimatedVideos
#https://en.wikipedia.org/wiki/Standard_RAID_levels
#https://www.youtube.com/watch?v=eE7Bfw9lFfs
#https://searchstorage.techtarget.com/definition/RAID


Phase II
Table of contents:
Abstract
I. Introduction
II. RAID
	i. Hardware vs Software RAID
	ii. Levels of RAID and its advantages and disadvantages
	
III. Conclusion


Citations/References:

"Standard RAID levels". Internet: www.en.wikipedia.org/wiki/Standard_RAID_levels, March 23, 2021 []

"(Almost) Everything You Need to Know About RAID". Internet: www.steadfast.net/blog/almost-everything-you-need-know-about-raid, May 26, 2020 [March 2010]

"What is RAID 0, 1, 5, & 10?". Internet: www.youtube.com/watch?v=U-OCdTeZLac, Aug. 10, 2015 []

"RAID 0, RAID 1, RAID 10 - All You Need to Know as Fast As Possible. Internet: RAID 0, RAID 1, RAID 10 - All You Need to Know as Fast As Possible Jan 31, 2013 []

Work assignments:
> Karl Escobar - Researcher
> Sofia Lopez - Researcher
> Jc Viray - Researcher



Phase III
Project title: A definitive explanation of RAID types and its use case scenarios
Team Members: Karl Escobar, JC Viray, Sofia Lopez

Abstract
	RAID (Redundant Array of Inexpensive Disks) is a type of storage configuration that has several benefits for whatever use case scenario you may have which can be used to improve performance or security of data transfer and storage (can be both). This paper will discuss the different types of RAID, the advantages and disadvantages and how it can be used to achieve better performance and/or better reliability. 
	
Topics/resource
RAID (Redundant Array of Inexpensive Disks)

	RAID is a type of storage system wherein the combination of small multiple disks into a single array, wherein these arrays are read by the computer as a single logical unit drive, are used to store and copy large amounts of data and to protect the data just in case there might be a drive or system failure. It also employs techniques such as disk striping, disk mirroring, and with parity. These multiple disks can be used to achieve different levels of data redundancy, data backup, enhance performance, error/fault tolerance, increased reliability and throughput depending on which type of RAID is being used.
	
● Hardware vs Software RAID
> Hardware RAID
- It does all the management of the RAID arrays, providing logical disks to the system and it can provide many different types of RAID levels simultaneously to the system. 
- Hardware RAID has dedicated controller which works independently from the operating system. This means more speed and reliability is possible for this configuration.
- Swapping hard drives out is made easier as well, just pull it out and replace with a new one.
- incurs additional cost due to needed hardware

> Software RAID
- Software RAID performs much better than Hardware RAID. It implements various RAID levels in the kernel disk code (block device) and offers a much cheaper solution.
-Cost is lower because no additional hardware is needed. 
-This gives better freedom with how you can setup your RAID arrays unlike with the hardware based where you are depended with the type of controller that you have.
-Since this software based and relies entirely with the stability of your operating system, this is less reliable and can be a bit slower compared to hardware based. This is also specific to the operating system that you have and cannot be setup with other computer.
-Disk replacement is a bit of a hassle too, as you have to set certain parameters to the software before you can pull out the erring hard drive

● Levels of RAID
- Data is distributed across different drives in several ways.

> RAID-0
	- It consists of striping but not mirroring or parity. Good for Heavy read operations and has a high-performance speed. You get combined storage space off all hard drives that are in this array. Downside is data is divided amongst all hard drives and if one disk fails data can be lost. 

> RAID-1
	- It consists of Mirroring. A literal 1:1 copy of your hard drive. Good for standard app servers, has a high fault tolerance and high read performance. Downside is lag for write ops, and storage is reduced by 1/2

> RAID-5
	- It consists of striping and parity. Good for normal file storage and App servers, has high speed and fault tolerance. A combination of the above raids. Downside is lag for write ops and storage is reduced by 1/3. 

> RAID-6
	- It consists of striping and double parity. Good for Large file storage and app servers, has extra level of redundancy and high read performance. Downside is low write performance and reduced storage by 2/5.

> RAID-10
	- It consists of striping and mirroring. Good for Highly utilized database servers, has high write performance and strong fault tolerance. Better than RAID 5 in backing up a disk. Downside is limited scalability and storage is reduced by 1/2. 

While RAID may seem like a good idea for backing up your data, it does not. It protects your hard drive or gives you the possibility of swapping your hard drive after a complete failure with data intact. A corrupted data will still be corrupted no matter what your RAID configuration will be. A regular back is still needed for that. 




