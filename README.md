---
title: DOCUMENTS REPOSITORY README
author: Decentralized Climate Foundation
date: 2023-02-08
category: README
layout: post
---

:space_invader:
[![GNUv1.3 License](https://img.shields.io/badge/License-GNU%20v1.3-yellow.svg)](https://opensource.org/licenses/) [![GitHub contributors](https://img.shields.io/github/contributors/PaganoBerserker/Rustbook.svg?style=flat)]() :space_invader:

# Rustbook
Rustbook

A "Rustbook" is an unofficial term that usually refers to books, tutorials, or documentation related to the Rust programming language.
Rust is a systems programming language known for its focus on safety, performance, and concurrency.
It is renowned for providing control over memory usage, which helps to avoid common errors like null pointer dereferences and data races.
Rustbooks can be created by the Rust developer community or by the official team behind the language.
These books are designed to teach and guide programmers in the process of learning Rust and understanding the key concepts of the language.
A Rustbook typically covers a wide range of topics, from the basics of the language to more advanced concepts, such as thread handling and concurrency, macro usage, library creation, etc.
In addition to theory, Rustbooks often include practical examples and exercises to help readers apply what they are learning.
The official and most well-known Rustbook is "The Rust Programming Language" (also known as "The Rust Book").

It is a comprehensive guide provided by the team behind Rust and is regularly updated to keep up with the latest language features.

It is widely considered an excellent resource for learning Rust and is available for free online.

To learn from a Rustbook, all you need to do is access the book online (if it is freely available) or purchase a copy if it is available in print or electronic format.

Then, you can read at your own pace, following the examples and exercises as you progress.

You can also use the book as a reference when working on Rust projects to recall specific concepts or solve challenges.

In summary, a Rustbook is a valuable tool for learning Rust and becoming proficient in this exciting programming language.

If you're interested in learning Rust, I recommend looking for "The Rust Programming Language" or any other available Rustbook to gain a solid understanding of the language and its unique features.

### Create

To carry out the project of creating a decentralized "Rustbook" for the documentation of the DECA Protocol, you can follow these steps:

Step 1: Research
Begin by researching the DECA Protocol and related concepts. Familiarize yourself with its principles, objectives, and how it is used in practice. Review existing documentation and any relevant resources available online.

Step 2: Set up the development environment
Make sure you have Rust and Cargo installed on your machine. You can follow the installation instructions on the official Rust website (https://www.rust-lang.org/tools/install). You will also need a text editor or IDE to write Rust code and Markdown for the documentation.

Step 3: Create the project structure
Create a new folder for your project and establish a basic structure to organize your files. You can use a structure like this:

```
- deca_project/
  |- src/              # Rust source files will be here
  |- docs/             # Documentation files in Markdown will be here
  |- README.md         # General information about the project
```

Step 4: Development
Start writing Rust code to implement the functions and features of the DECA Protocol. Use the files in the `src/` folder to organize your implementations. Be sure to follow Rust's best practices and properly document your code.

Step 5: Documentation
Create Markdown documents to explain the workings of the DECA Protocol, implementation details, usage examples, and any other relevant information. You can use a folder named `docs/` to organize your documentation files.

Step 6: Create the decentralized "Rustbook"
Use the mdBook tool to create the "Rustbook" from your Markdown documentation files. You can install mdBook by following the instructions on its website (https://rust-lang.github.io/mdBook/). Then, run the `mdbook build` command in the main directory of your project to generate the "Rustbook" in HTML format.

Step 7: Add information to README.md
Update the README.md file in the main project directory to include a description of the project, details about the DECA Protocol, links to the documentation, and any other relevant information.

Step 8: Publishing and dissemination
Once you have completed the "Rustbook" and documentation, you can publish it online for others to access. You can use document hosting platforms like GitHub Pages to host the "Rustbook" and documentation.

Also, consider spreading the word about the existence of the "Rustbook" in Rust and DECA Protocol-related communities and forums so that more people can benefit from your work.

Remember that the key to creating a successful "Rustbook" is accuracy, clarity, and good documentation. Make sure to keep the project up-to-date as the DECA Protocol evolves and consider accepting contributions from the community to improve the content and quality of the "Rustbook." Good luck with your project! 


# IPFS

IPFS, which stands for InterPlanetary File System, is a protocol and decentralized network designed to change the way content is stored, distributed, and accessed on the Internet. It was created by Juan Benet in 2014 and aims to address some of the key challenges facing data storage and distribution technologies in the current web.

The central feature of IPFS is its focus on content-based distribution rather than location-based. Instead of relying on IP addresses or domain names to access files, IPFS uses a system of unique addresses based on the content's hash. This means that each file or set of data has a unique hash that serves as its address, allowing for a more efficient and redundant way of storing and distributing information.

The main features of IPFS include:

1. **Decentralized distribution:** IPFS operates on a decentralized network, meaning files are stored and distributed across a network of interconnected nodes, rather than relying on a central server. This can enhance resistance to censorship and availability of content.

2. **Peer-to-peer (P2P) network:** Each node in the IPFS network can act as both a client and a server, enabling direct content distribution between nodes without the need for a central server. This reduces the load on individual servers and enables greater performance and scalability.

3. **Hashing and unique addresses:** Each file or set of data in IPFS is identified by a unique hash that is calculated from the content itself. This allows for precise and unique referencing of any file, regardless of its physical location in the network.

4. **Redundant storage:** Since files are distributed across multiple nodes, the inherent redundancy in the IPFS network can improve the availability and speed of content access. If one node is unavailable, other nodes can provide the same content.

5. **Caching and speed:** IPFS includes a caching system that helps speed up access to files. If a node already has a copy of a file, it can serve it directly.

6. **Resistance to censorship:** Due to its decentralized nature and lack of a single point of control, IPFS is more resistant to censorship and content removal.

IPFS has applications in various areas, including content distribution, software version management, website publishing, and the creation of decentralized applications (dApps). However, it also presents challenges in terms of widespread adoption and compatibility with existing web infrastructure.


# How to install IPFS.
## Linux.

Warning: You must execute the commands where indicated, and if it is not indicated it is preferable to execute it again in the root of the user, in this case the ipfs user.

1. Open the terminal and update the system packages:
```linux
sudo apt-get update
```
2. Download the IPFS package from the IPFS downloads page:
```linux
wget https://dist.ipfs.io/go-ipfs/v0.10.0/go-ipfs_v0.10.0_linux-amd64.tar.gz
```
3. Extract the downloaded package:
```linux
tar xvfz go-ipfs_v0.10.0_linux-amd64.tar.gz
```
4. Navigate to the newly extracted directory:
```linux
cd go-ipfs
```
5. Run the installation script:
```linux
sudo ./install.sh
```
6. Verify that IPFS has been installed successfully:
```linux
ipfs --version
```
7. If the installation was successful, initialize the IPFS node:
```linux
ipfs init
```
8. To verify that the node has started successfully, run the following command:
```linux
ipfs daemon
```
9. If the node has started successfully, you can use the IPFS client to add and download files:
```linux
ipfs add <path to file>
ipfs cat <hash of file>
```

Warning: You must execute the commands where indicated, and if it is not indicated it is preferable to execute it again in the root of the user, in this case the ipfs user.

## Compiling Go

```linux
wget https://golang.org/dl/go1.20.linux-amd64.tar.gz
tar -xvf go1.20.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
source ~/.bashrc
source ~/.zshrc
go version
```

```linux
apt install git gcc
snap install go --classic
mkdir -p ~/Applications
git clone https://go.googlesource.com/go ~/Applications/go
cd ~/Applications/go/src
git checkout go1.18
./make.bash
```

Warning: You must execute the commands where indicated, and if it is not indicated it is preferable to execute it again in the root of the user, in this case the ipfs user.

Make sure to replace go1.18 with the latest Go version.

Edit your ~/.profile to access this new Go installation.

```linux
# Go
PATH="$HOME/Applications/go/bin:$PATH"
PATH="$HOME/go/bin:$PATH"
```

## Compiling IPFS

```linux
apt install make pkg-config libssl-dev libcrypto++-dev
mkdir -p ~/Applications
git clone https://github.com/ipfs/go-ipfs.git ~/Applications/ipfs
cd ~/Applications/ipfs
go get github.com/lucas-clemente/quic-go@go118
```

I follow exactly this guide install openssl:

```linux
git clone --depth 1 https://github.com/openssl/openssl
cd openssl
./config enable-tls1_3 --prefix=/home/team1/openssl
sudo make
sudo make install
sudo env GOTAGS=openssl make install
```
Warning: You must execute the commands where indicated, and if it is not indicated it is preferable to execute it again in the root of the user, in this case the ipfs user.

# Adding a service

Configure your service as follows (this is a sample since DECA was used).
Enter the following command to be able to configure the respective file (ipfs.service):

```linux
sudo vim /etc/systemd/system/ipfs.service
```

```linux
[Unit]
Description=InterPlanetary File System (IPFS) daemon
Documentation=https://docs.ipfs.io/
After=network.target

[Service]
Type=notify
ExecStart=/home/ipfs/go/bin/ipfs daemon --enable-gc=true --migrate=true
ExecStop=/home/ipfs/go/bin/ipfs shutdown
Restart=on-failure
KillSignal=SIGINT

[Install]
WantedBy=default.target
```



# Licence.
```
Copyright (C) DECENTRALIZED CLIMATE FOUNDATION A.C.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License". 
```


