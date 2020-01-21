---
# front matter tells Jekyll to process Liquid
# this is yaml
my_number: 5
---

### Promoting and enabling the future of the Internet will have profound economic consequences as billions of new "Things" join the fray. 

I will attempt to define what is needed now to promote that IoT revolution. Then I will present the methodology behind a new service to resolve issues. Finally, a detailed specification of how the service would work is presented here. Due to the magic of software systems the specification used is enough to bring the service into existance.

It's going to take more than one page. Here's the outline:

* We'll define "Computer". Computers can be connected to each other with wires or radio.

* We'll define "Network" and then define "Network Of Computers" or "Computer Network".

* From this we can define an "Intranet".

* Then we can define the "Network of Intranets" which is "The Internet" that we all know and love.

* The Internet uses, at it's lower level, the "Internet Protocol", or "IP". We'll discuss the useful characteristrics of that.  

* We'll define how every computer that has an "IP Address" can send a "Packet" to *any* other computer on The Internet. 

* The IP packet delivery is "Unreliable" and "Insecure" so we'll define that and note that other "Layers above IP" provide reliability and security so it's enough to just invent IP and let the rest be follow-up.

* IP addresses are numbers but people prefer to remember names (eg. google.com and not 216.58.192.142) so we'll define how the "Domain Name System" or "DNS" was created to "lookup" the IP addresses. 

* DNS is a "centralized system" aka a "Monopoly" so it is managed by a non-profit organization.   

* Now we can discuss the difference between "Mesh Routing" and "Hierarchical routing" and how IP is more mesh and DNS is more hierarchical.

* The IP addresses which are so useful have been mostly exhausted so we'll define "IPv6" which is meant to remedy that. 

Then:

* We can define a "Thing" as being mostly similar to a computer. We will define how they are different (there's no use sending advertisement to them).

* Then we can define a "Network of Things" and how that is commonly done these days. We will note that Things may not always have IPv6 addresses. 

* Messages are commonly passed between things using a technique called "Pub/Sub" so that will be defined.

* At this point we can observe that there are many Intranets of Things but there is *not* an "Internet of Things" despite the fact that people use the acronym "IoT".

* Furthermore, there is no DNS for the things and it should be obvious that this would need to be non-profit and similar to the existing DNS with some changes or upgrades. 

* We can design a name system for the things. I don't know its name. 
    * The price is specified in "micro dollars per month per device" so it's not free but is extremely inexpensive.
    * The things will announce their own names and we'll see that this is functionally equivalent to a "subscribe".
    * We will see that sending messages up the DNS hierarchy with a "publish" is functionally equivalent to sending through IPv6. IPv6 is an optimization more useful for larger messaging rates and it will be good to have a fallback.

* We will design a system for getting remunerated for the costs involved. 
    * Society is unlikely to allow profit taking or rent seeking. This makes funding the engineering development of the core-infrastructure impossible. 
    * The tools and methods used to specify the existence and operation of society wide massive internet infrastructures are so very powerful now that it's in the range of possibilities for a singe altruistic actor.

The other way to look at it is that Paul Mockapetris is my hero. -- Or -- If you want to control your home thermostat from work without going through a big tech company you're going to want to back this proposal. If you're sick of otherwise functional devices becoming useless when their manufacturer goes away then you've come to the right place. One internet for all the things. 

I think should be clear at this point that these developments are __inevitable__ in one form or another. I'm working on it. 

<div id = "atwheader" >
- Alan Tracey Wootton -
</div>

<!--  {{page.my_number}} -->

<!-- <div id="commento"></div>
<script src="https://cdn.commento.io/js/commento.js"></script> -->
