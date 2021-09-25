# How I explained REST to my brother:

## Who is Roy Fielding?

Roy T. Fielding, Senior Principal Scientist at Adobe, is known for his pioneering work on the World Wide Web, open source, and software architecture. He wrote the standards for HTTP/1.x and URI, has been a contributor to many other Web technologies, and defined the REST architectural style. Dr. Fielding is a founder of the Apache HTTP Server Project, Chairman of the Apache Software Foundation, member of the ASF board of directors, and author of the Apache License 2.0. He has been honored with the ACM Software System Award, ACM SIGSOFT Impact Paper Award, OSCON 2000 Appaloosa Award for Vision, ICSE Most Influential Paper, and MIT Technology Review’s first TR100. Dr. Fielding received his Ph.D. in Information and Computer Science from the University of California, Irvine.

## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

Because they weren’t designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn’t have those requirements. You just needed to talk to a small group of machines.

- What does a GET do?

it is used RETRIEVE information from a different system

- What does a POST do?

is used when one system wants to ADD something to another system

- What does PUT do?

is used when one system wants to REPLACE something in another system

- What does PATCH do?

when a system need to do a partial update
