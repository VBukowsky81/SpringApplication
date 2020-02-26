# SpringApplication
Spring, Dependency Injection, JPA

Hello, everyone!

PS. Now a month later, I would rewrite this description completely. But I am too lazy. Turns out Spring implements ALL creational design patters. And dependency injection is not even officially a design pattern, though it technically is. Learning lots.

Earlier description:
I wanted to present this great example, in my opinion, of a basic Enterprise level Spring application, dependency injection and generally Spring Data. Dependency injection sounds really cool, and it IS actually cool. DI is really hard to describe, and I have not heard a good enough SHORT description of it. 

I would say, DI are ways to inject yourself into object creation process. Why do this? Because you can insert/inject all sorts of data automatically/from external sources, for example, before object is created. Or directly after. This DECOUPLES object creation process, and gives you ways to automate it, manage it, generally gives a way to work with it. 

Spring uses two types of DI - constructor and setters. All these are part of core language mechanics, simply neat ways to work with basic language toolset. Constructor injection, for example, makes use of ability to set states at object creation, with a constructor. Constructor values can then be set independently of the object creation process itself.

I am still rather new to this huge area of depenedency injection subject matter.

The idea here is great, if I fully understand it. Mass production of objects, with externally sourced inputs. Profiles, environment variables, Spring expressions(SpEL), etc. And there are many more applications, I am sure. Like scripting languages, for example.

I am not taking credit for this work, but I would have build this example in a similar way. There is a general template to this anyway, meaning that standard setups are going to be nearly identical.

Best Regards,

Vic


