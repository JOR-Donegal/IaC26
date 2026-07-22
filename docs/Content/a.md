# Week 1

I provide a link to my [Getting Started](https://jor-donegal.github.io/GettingStarted26) notes in every module. Make sure you have read this and are fully familiar with the content.

So what is _Infrastructure as code_?

Long ago I used to teach separate modules in topics associated with systems engineering at undergraduate level. We would always have a stream of networking modules which went from basic communications theory to advanced modern secure networking. We might have a separate subject in computer architecture, which would get us from the basics all the way through to understanding the specification of a modern server. And then operating systems, covering Windows and Linux was a separate subject again. And the systems engineering of both of those topics was yet another specialized subject. And don't get me started on firewalls! As a collective way of describing these topics, I've been using the term technical infrastructure for many years.

But then everything changed and from 2006 onwards, we've had the capability of producing these server instances and network appliances as virtual devices. It's what cloud computing is all about. If you need a server or a network switch or a firewall, you just create it as a virtual device.

For a range of reasons, it is advantageous for us to be able to script the creation of all these devices and their configuration.

1. Once a script is ready, we can use it to create an instance of an appliance almost instantly. This is very efficient.
2. If the script was right once, it's always going to be correct within the same context of usage. This accuracy and repeatability cannot be matched my manual processes.
3. Depending on the language and configuration files, scripts can be self documenting and the code that we use to create an infrastructure can also be the basis for the documentation of that infrastructure.
4. As that code can be reused, we suddenly have part of our solution for business continuity in the event of things going wrong.
5. The code that we use to create appliances, and infrastructure can be audited by humans, by automated tools, and more recently by AI tools.

A proven and tested script allows me to configure an appliance instance in a particular context. But it can also be the basis for large scale automation. If I know how to configure Apache securely on an Ubuntu instance, I just need to add a little automation to do that at scale on 200 servers. And I can also script that automation!

A final step. In the world of coding, we have the concept of continuous integration and continuous deployment. I make a change to my code, and I press go! The code changes tested then its integration with other modules is also tested. It's automatically pushed to a test environment where other processes can evaluate its suitability for release. If it's accepted for release it can automatically roll to a deployment stage. We've been doing all of this in an automated way for years. If our infrastructure is a group of scripts and configuration files, we can do the same thing with it.

For this week, there are some links below to some (light!) reading.

1. Read my background to general computing.