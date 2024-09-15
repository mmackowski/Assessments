**Matt Mackowski / CIDM 6350**

# Networking and Cybersecurity – Overview

There was a time in the not too distant past when networking/cybersecurity were separate disciplines from web development. The network admin ran the cables and configured the domain accounts, while the developer sat in his cave and pounded out code. Those days are long gone. Security is far too important today; as a developer, if I’m not integrating sound security practices into my designs, I’m being culpably negligent, putting my organization at risk. Even more than that, though, most of what I do has to center around the basics of network architecture (HTTP), and I must consider firewalls, VPNs, configurations in Cloudflare.

That said, I would only claim that my networking/cybersecurity skills are competent for a web developer, and this is an area in which I can always improve. As an aside, the two classes I took in this area were different in subtle but significant ways: CIDM 6340 had more of a technical focus, whereas CIDM 6341 emphasized human issues. Both were excellent, I learned a great deal.

## What Do I Know

****Social Engineering.**** In many ways this has become the single most important element related to networking and cybersecurity. As technology and security controls improve, it becomes more difficult for bad actors to breach systems using tech alone. Humans remain the easiest access point. Like many organizations, mine requires quarterly security training, and about 90% of that training revolves around social engineering. I don’t think it is possible to be a valuable member of any company without taking your security responsibilities seriously.

****Authentication/Authorization.**** Virtually all websites that handle data in any serious form must take into account auth practices. Every application I develop integrates some form of authentication/ authorization, which for my organization today means oAuth or SAML (mostly oAuth). This of course doesn’t just mean who can access the app itself (authentication) but what areas of the app they have access to (authorization). It’s been more than a decade since I’ve developed anything for the web that didn’t have some for of integrated security.

****Common Web Attacks.**** In recent years, all developers, myself included, have been schooled on how to code against common web attacks like SQL injection and cross site scripting. We’ve also become familiar with monitoring/security tools that raise awareness to network-related attacks like denial of service.

****Basic IT Security Controls.**** We’ve also been trained on designing around basic security concepts like the principle of least privilege. Proper use of design principles like encapsulation also help to make applications secure. I am responsible for my application passing our quarterly PCI scan.

# What I Don’t Know

****Asset Inventory.**** CIDM 6341 was a challenging course, because it asked me to consider aspects of web development that I had previously ignored, three of which I’ll note here, starting with asset inventory. When you’re knocking out code, it’s easy enough to say “that’s someone else’s job,” but as someone who is responsible for making sure mission-critical web applications are up and running, knowing what the organization has and what it needs is something of which I should be more aware.

****Threat Assessment and Contingency Planning.**** As noted above, I’m fine with threats like social engineering and SQL injection, but what are the changes of the top developer on my team leaving (taking with him vital institutional knowledge)? I’m used to having to scramble when our application host provider goes down, but have I adequately planned in advance for those certainties? Clearly, I have not. The development cycle moves so quickly you feel like you don’t have time to stop, assess, and plan. But I have a strong feeling this will come back to bite me soon enough.

****IT Infrastructure.**** Ok let’s be honest, I’m still not tweaking domain accounts or tuning VPN settings. There is a lot about network administration about which I am, well maybe clueless is too strong, so let’s say ‘not proficient.’

## What I Wish I Knew and Didn’t Realize I was Missing

Honestly, I wish there I knew more in all aspects of networking and cybersecurity. This is not an exaggeration.

As perviously mentioned, until entering this program, I quite literally didn't realize that I was missing what you might call the 'managerial' elements of cybersecurity (asset inventory, etc.). And as it so happens, in the past year or so I've moved into a role that has more of a managerial bent (team lead). There is now some increased urgency for me to improve in these areas, though I'm not entirely sure how to do so. Our ongoing move to Salesforce may present an opportunity to work on some of these skills (particularly somehting like asset inventory), but the transition process itself is consuming so much time it's hard to find room for extras.

And even in terms of IT infrastructure, my skills need to improve. My organization is currently moving some key assets to Microsoft Azure; it's only a matter of time before I'm staring at an Azure dashboard configuring network and application resources.

## Integration

Networking and cybersecurity is woven into everything I do as a developer, and certainly foundational to the other areas. And I know enough to keep the lights on, but I'm not sure that will be enough going forward.
