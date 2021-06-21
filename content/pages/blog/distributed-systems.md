---
title: Distributed Systems
date: '2021-06-21'
categories:
  - content/data/categories/category-b6twnug29.json
tags: []
excerpt: lorem-ipsum
thumb_image_alt: lorem-ipsum
image_alt: lorem-ipsum
image_position: top
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
layout: post
author: content/data/team/person-1sqlcbe74.json
---
## What are distributed systems and why should we care?

Have you ever wondered how Google handles billions of requests per day, the magic behind cloud computing, and what even made a decentralized currency possible? The technology behind these wonders is distributed systems. The computer scientist Andrew Tannenbaum defines it as "a collection of independent computers that appear to its users as one computer". To elaborate, a distributed system is a collection of independent hardware/software components, called nodes, that are networked to work together coherently to fulfil one end goal. If you are still confused, just as many people may work together on a single problem, in a distributed system many computers work together usually to solve a computationally difficult problem, simulating a single massive computer. 



## How it works

In order to make a distributed system, you need multiple nodes, some resources and middleware to tie it up altogether. A node can be either hardware or software which has its own memory. An example is the internet which is a giant open group of nodes(host computers that are identified by an IP address). Homogeneity is not required for these nodes which means that can have different operating systems and technologies. Furthermore, there shouldn’t be a shared clock or memory. Finally, these nodes should work concurrently, meaning that multiple tasks/computations happen at the same time.  A resource can be anything - it’s simply an asset that the nodes can access and take advantage of. The middleware is the backbone of a distributed system since it provides a logical layer that connects the nodes together making them appear as a single computer. It is often imagined being like plumbing because it connects all the nodes, allowing data to be passed between them. Applications are built on top of the middleware. 



## Examples of implementations

A notable example, which was developed and initially used by Google for its search engine, is a framework called MapReduce which effectively divides up a task across numerous machines. MapReduce breaks down what you are trying to do into three stages: map, shuffle and reduce. A famous example to explain how it works is that of counting the number of occurrences of words appearing in very large documents. Let's say that we have got 2 computers and 16 documents. We would start by distributing the documents between the computers (so 4 documents for each computer). Now what each computer is going to do is count the number of time each word appears. So for example computer 1 would compute a bunch of keys and values from the documents it was assigned (such as happy:15 and learn:10) and computer 2 would do the same and produce (happy:123 and learn:5). At this stage, there is no communication between these machines. At the shuffle stage, keys are grouped based on their key and then processed onto the reduce stage. For example, the two computers will communicate and shuffle/aggregate their results so that the same keys are together. At the reduce stage, all the results are taken from the map stage and combined to get a finalized result. So in this case, at the reduce stage we would get a result that "happy" appears 138 times (happy:15 + happy:123) and "learn" appears 15 times (learn:10 + learn:5). Thus, this is a way in which a single computation is distributed among many machines.

Another example of distributed systems that we interact with every day is DNS (Domain Name System). A DNS is simply a directory of names (specifically website URLs) that are matched with IP addresses - imagine a phone book/contacts list. This domain name service is maintained and operated by many independent organizations (such as ICANN) and a network of thousands of servers that interact with each other so that the requested website is served on our browser. 

The final example is BitTorrent, a peer-to-peer file-sharing system that is used to distribute large amounts of data over the internet.  Rather than downloading a file from a single source server, the BitTorrent protocol allows users to join a “swarm” of hosts to download and upload from each other simultaneously. The first step in this process is the user downloading a torrent file that contains information about the files to be shared, and also a list of the trackers which are a server that tells you where to contact other computers that are also downloading this file. When the user opens this torrent file with a BitTorrent client, the client will know what it should download, and it will then contact the tracker and download a list of peers, attempting to connect to them. Then in the “initial seeding” phase, a small chunk of data would be uploaded to each peer. These peers will then become seeders and will start uploading their own chunk to others while at the same time downloading other chunks from other peers. This results in the user having many pieces that make up the file they want, which the BitTorrent client will sort so that the user gets all the data in a usable and appropriate way at the end. This peer-to-peer architecture is much faster and more convenient when sharing a file with large groups of people than on a client-server. 

To exemplify how significant and ubiquitous distributed systems are, revolutionary technology such as cloud computing and blockchain wouldn't exist today without it. 



## Types of Distributed Architecture

Cluster computing (centralized, closely connected identical computers. This used for high-performance and minimum downtime. An example is one of the world's most powerful supercomputers, IBM's Sequoia.)

Grid Computing (computers that are placed in many locations around the world, not necessarily close to each other. This is often used for large data repositories and high computing power requirements. An example is BOINC - developed by UC Berkeley - which lets you contribute computing power on your home PC to projects doing research in many scientific areas.)



## Advantages

The most obvious advantage of using a distributed system is that it improves reliability since instead of relying on a single powerful computer that can stop working due to individual components malfunctioning or a power outage. On the other hand, in a distributed system even if one computer/server fails, the other computers/servers won’t be affected and the program will continue to run - this is called fault tolerance. Furthermore, distributed systems are usually favoured because they effectively scale horizontally. For example, when scaling vertically, there is a hard limit to the extent you can upgrade your machine, however when scaling horizontally, there is no such cap to how much you can scale since all you have to do is add another node when the demand is high. This also proves to be more cost-effective. In addition, an often overlooked feature of distributed systems is the ability to reach a consensus which is vital for online payments and blockchain. Consensus, in essence, is getting all the nodes to agree on a value which is important to improve fault-tolerance and trust (which is mandatory in the case of online payments). Finally, distributed systems are particularly advantageous when used in resource sharing applications as shown in the BitTorrent example above.



## Disadvantages

Like all things in the world, distributed systems are not without their flaws. Notably, there are several security issues due to its open nature, so it is difficult to provide adequate security to all nodes and connections. Furthermore, since this system is built upon the ability of the nodes to communicate with each other, overloading may occur in the network if all the nodes try to send data at once. Finally, the management of tens if not thousands of nodes is very difficult as it also means that it is often easy to detect failures or optimize any performance bottlenecks. 
