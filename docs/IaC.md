# Background

So what is _Infrastructure as code_?

Long ago I used to teach separate modules in topics associated with systems engineering at undergraduate level. We would always have a stream of networking modules which went from basic communications theory to advanced modern secure networking. We might have a separate subject in computer architecture, which would get us from the basics all the way through to understanding the specification of a modern server. And then operating systems, covering Windows and Linux was a separate subject again. And the systems engineering of both of those topics was yet another specialized subject. And don't get me started on firewalls! As a collective way of describing these topics, we use the term _technical infrastructure_.

But then everything changed and from 2006 onwards, we've had the capability of producing these server instances and network appliances as _virtual devices_. It's what _cloud computing_ is all about. If you need a server or a network switch or a firewall, you just create it as a virtual device; an appliance which lives and executes in the memory of another computer.

For a range of reasons, it is advantageous for us to be able to script the creation of all these devices and their configuration.

1. Once a script is ready, we can use it to create an instance of an appliance almost instantly. This is very efficient.
2. If the script was right once, it's always going to be correct within the same context of usage. This accuracy and repeatability cannot be matched my manual processes.
3. Depending on the language and configuration files, scripts can be self documenting and the code that we use to create an infrastructure can also be the basis for the documentation of that infrastructure.
4. As that code can be reused, we suddenly have part of our solution for business continuity in the event of things going wrong.
5. The code that we use to create appliances, and infrastructure can be audited by humans, by automated tools, and more recently by AI tools.

A proven and tested script allows me to configure an appliance instance in a particular context. But it can also be the basis for large scale automation. If I know how to configure Apache securely on an Ubuntu instance, I just need to add a little automation to do that at scale on 200 servers. And I can also script that automation!

A final step. In the world of coding, we have the concept of _continuous integration and continuous delivery_ (CI/CD). I make a change to my code, and I press go! The code change is tested then its integration with other modules is also tested. It's automatically pushed to a test environment where other processes can evaluate its suitability for release. If it's accepted for release it can automatically roll to a deployment stage. We've been doing all of this in an automated way for years. If our infrastructure is a group of scripts and configuration files, we can do the same thing with it.

A final word.

What about AI?

Surely nobody needs to do scripting or even programming anymore?

Not true.

If you are an expert in scripting or coding and you have expertise in the domain in which you are working, then you understand what you are doing. Add in modern AI tools, and your efficiency and productivity are enhanced. You still need to understand the overall project, you need to know how to correctly prompt the tools you are using for assistance, and you need to understand the code that comes back from the tool set you are using. You need to know how to test that code to make sure it does what you intended. Modern AI tools allow a smart person to be very very productive.

In this module, I aim to start making you that smart person. At the end of the module, once you know how to script and test, then we can introduce the tool sets that in reality we will all use in a production environment.

In these documents, there are several key terms. These will be _italicized_. You may need to look up these terms to get a full understanding of them. Commands are generally shown in __bold__.

In these notes, an _ISO file_ is an image of a DVD used for installation purposes.
