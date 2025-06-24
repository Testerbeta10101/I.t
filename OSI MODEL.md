---
share_link: https://share.note.sx/zyi4v0yi#+uJSo7rkQVCvviSx+jHLadhbwaaw/VPPC1uZAph20eA
share_updated: 2024-10-07T00:04:56-05:00
---




# What is the Osi Model 

The open system interconnection (OSI) model describe seven layers that computer system use to communicate over a network. It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980s.


The modern internet is not based on OSI, but on the simpler [[TCP]] /IP model. However, the OSI 7-layer model is still widely used, as it helps visualize and communicate how network operate, and helps isolate and troubleshoot network problems.


OSI was introduced in 1983 by representatives of the major computer and telecom companies, and was adopted by IOS as an international standard in 1984.



## OSI Model Explained: The OSI 7 Layers

![[Pasted image 20240606111447.jpg]]

We'll describe OSI layers "top down" from the application layer directly serves the end user, down to the physical layer.


7.  ![[Application Layer]]
***

6.  ![[Presentation Layer]]
***



5.  ![[Session Layer]]
***


4. ![[Transport Layer]]

***


3.  ![[Network Layer]] 

***


2.  ![[Data link Layer]]
***


1.  ![[Physical Layer]]

***


### Advantages of OSI Model

**The OSI models helps user and operators of computers networks**


- Determine the required hardware ans software to build network.
- Understand and communicate the process followed by components communicating across a network.
- Perform troubleshooting, by identifying which network later is causing an issues and focusing efforts on that layer.


**The OSI model helps network devices manufactures and networking software vendors**


- Create devices and software that can communicate with products from any other vendors, allowance open interoperability 
- Define which parts of the network their product should work with.
- Communicate to users at which network layer their product operates - for example, only at the application layer , or across the stack.


## OSI VS. TCP/IP Model

![[Pasted image 20240606124009.jpg]] ![[Pasted image 20240606124013.jpg]]

The Transfer Control Protocol/internet Protocol (TCP/IP) is older than the OSI Model and was created by the US Department of Defenses (DoD). A key difference between the model is that TCP/IP is simpler, collapsing serveral OSI layers into:


- OSI layers 5,6,7 are combined into one Application Layers in TCP/IP
- OSI layer 1,2 are combined into one Network Access Layer in TCP/IP -however TCP/IP does not take responsibly for sequencing and acknowledgement functions, leaving these to the underlying transport later


Other important differences:


- TCP/IP is a functional model designed to solve specific communication problem, and which is based on specific, standard protocols. OSI is a generic , protocol-independent model intended to describe all forms of network communication.
- In TCP/IP, most application use all the layers, while is OSI simple application do not use all seven layers. Only layers 1, 2 and 3 are mandatory to enable data communication.