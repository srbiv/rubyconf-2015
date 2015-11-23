# RubyConf 2015 - San Antonio

This is covers the talks I attended. Since all these talks will be published on
[ConFreaks] in the upcoming week, I won't go into a ton of detail on each talk.
Instead, I hope to provide the reader with enough information for them to make
decision on whether or not they should watch the talk on ConFreaks. Once the videos
are released I plan to update each talk with a link to the associated video. If
the speaker had previously given the talk, I will also link to it so the reader
doesn't have to wait.

## Day One

### Keynote: Consequences of an Insightful Algorithm
#### Carina C. Zona [@cczona](https://twitter.com/cczona)

[Video of talk](https://www.youtube.com/watch?v=v76c9aMn_qw)

Tags: Ethics
Recommended for: Everyone

Carina shares several examples of algorithms that had unintended consequences.
In the examples, companies implement powerful algorithms, often times with the
best intentions. However, these companies didn't carefully think through all the
consequences for their users. Their users ended up embarrassed and hurt. Also the
companies received negative PR.

### How to Stop Hating your Test Suite
#### Justin Searls [@searls](https://twitter.com/searls)

[Video of talk](http://blog.testdouble.com/posts/2015-11-16-how-to-stop-hating-your-tests.html)

Tags: Technical, Testing
Recommend for: Developers

Justin explains some common pains of testing including: slow tests suites,
failures in production despite test coverage, testing large classes, and large
test setups. He shares approaches to mitigate these pains on existing projects and
ways to avoid them altogether on new projects. Also discusses the [Given] gem.


### Inside Ruby's VM: The TMI Edition.
#### Aaron Patterson [@tenderlove](https://twitter.com/tenderlove)

[Video of talk](https://www.youtube.com/watch?v=CT8JSJkymZM)

Tags: Very Technical, Very Funny
Recommend for: Fans of @tenderlove, Experienced Developers

Aaron starts of with some Texas sized jokes then take attendees on a very technical
whirlwind tour of Ruby's VM.

### The Art of Ruby Technical Interviews
#### Chris Mar [@cmar](https://twitter.com/cmar)

[Video of talk](https://www.youtube.com/watch?v=nZNfSQKC-Yk)

Tags: Career Development
Recommended for: New Developers

Chris gives a step by step guide to getting a job as a new developer. He covers
resume building, answering hard interview questions, and how to practice for an
interview.

### Seven Habits of Highly Effective Gems
#### Mat Brown [@0utoftime](https://twitter.com/0utoftime)

[Video of talk](https://www.youtube.com/watch?v=tqLbgS0fw5c)

Tags: Open Source
Recommended for: Developers

Mat provides a checklist for gem authors.
1) Provide a small set of commands to get started in the README
2) Long READMEs are great, see [Sinatra's]
3) Document your code with YARD
4) Use semantic versioning, try to avoid breaking changes
5) Pick the right level of abstraction for your public API
6) Make test suite easy for contributors to use
7) Use Rubocop to avoid style discussions on PRs

### I Estimate this Talk will be 20 Minutes Long, Give or Take 10 Minutes
#### Noel Rappin [@noelrap](https://twitter.com/noelrap)

[Video of talk](https://www.youtube.com/watch?v=jBMwT53oGsM)

Tags: Agile
Recommended for: Developers, Project Managers, Customers, Sales People

Noel give advice on how to estimate work for clients. He discusses the pressures
of estimating client work; both internal and external. Then he recommends breaking the
work down into the smallest possible units and rating the complexity of those task.
From he offers some simple math to figure out ranges that will allow you to come up
with an estimate. Finally, he covers presenting these estimates.

### Keynote: Stupid Ideas For Many Computers
#### Aja Hammerly [@thagomizer_rb](https://twitter.com/thagomizer_rb)

[Video of talk](https://www.youtube.com/watch?v=_O1MGHcsQCI)

Tags: Fun, Distributed Computing
Recommended for: Developers

Aja talks about using the cloud to do "stupid" things with Ruby and Kubernetes.
She uses Rinda::Tuplespace to do sentiment analysis on emojis on twitter. This was
one of my favorite talks.


## Day Two

### Keynote: Leagues of Sea and Sky
#### Jeff Norris [@DrJeffNorris](https://twitter.com/DrJeffNorris)

Tags: Amazing Presentation Tech, History, Collaboration
Recommended for: Everyone

[Video of talk](https://www.youtube.com/watch?v=BZg75PlmzXI)

Jeff gives a history lesson in collaboration (or lack there of). His presents his
talk in using tricks I have never seen used in a talk. Very entertaining while
discussing the value of collaboration and the importance of recognition of everyone
involved.


### A Muggle's Guide to Tail Call Optimization in Ruby
#### Danny Guinther [@dannyguinther](https://twitter.com/dannyguinther)

Tags: Recursion, Performance
Recommended for: Developers

Jeff explains Tail Recursion and tail call optimization. Tail call optimization
has been avaiable since 1.9.2. He shows how to enable it. He ends the talk with
discussing the benefits of tail call optimization and why you might not want to
enable it.


### Working Compassionately with Legacy Code
#### [Amar Shah](

[Video of talk](https://www.youtube.com/watch?v=JC4mS7sYQlU&list=PLlCa6FFUimCWanyRj0ilIeF2yt4FEHucf&index=2)

Tags: Legacy Code, Happiness
Recommended for: Developers

Amar shares a personally story of dealing with legacy code. He talks how easy it
can be to get angry at the code and at the previous developers. Instead of
indulging anger, Amar suggest applying cognitive restructuring to help better
reason with the situation. You can use the legacy code as a learning opportunity.
If the legacy code make you scared and sad it could be because you are working in
an culture of blame. Finally, Amar says that3w3w you have to know your limits and always
have an exit strategy when dealing with legacy code.

### Everything You Know About the GIL is Wrong
#### Jerry Antonio [@jerrydantonio](https://twitter.com/jerrydantonio)

[Slides from talk](http://www.slideshare.net/JerryDAntonio/everything-you-know-about-the-gil-is-wrong)

Tags: Concurrency, Performance
Recommended for: Developers

Jerry is the creator and maintainer of [concurrent-ruby](https://github.com/ruby-concurrency/concurrent-ruby). He demonstrates ways to use concurrency patterns in Ruby to increase performance
of I/O heavy tasks. He discusses the difference between concurrency and parallelism
and how the GIL works.

### The Hitchhiker's Guide to Ruby GC
#### Eric Weinstein [@ericqweinstein](https://twitter.com/ericqweinstein)

[Slides from talk](https://speakerdeck.com/ericqweinstein/the-hitchhikers-guide-to-ruby-gc)

Tags: Garbage Collection, Performance
Recommended for: Developers

Eric guides us through the changes made to Ruby's garbage collection from 1.8.7
to 2.2. He describes how Ruby's garbage collection currently works and shows
some ENV variables you can use to tune Ruby's GC.

### Ruby's Environment Variable API
#### Jack Danger Canty [@jackdanger](https://twitter.com/jackdanger)

Tags: Environments, Bundler, Load Paths
Recommended for: Developers

Jack describes what ENV variables are. He shows how Ruby, RubyGems, and Bundler use various
paths to load the proper code for your environment.

### How to Crash an Airplane
#### Nickolas Means [@nmeans](https://twitter.com/nmeans)

[Video of talk](https://www.youtube.com/watch?v=S2FUSr3WlPk)

Tags: Collaboration, Failure
Recommended for: Everyone

Nickolas tell the story of United flight 232 and how the flight crew worked together
to save lives when an impossible failure happens. The crew followed the recently
implemented Cockpit Resource Management procedures which gave everyone in the crew
a voice instead of just relying on the captain.


### Bikeshed! Live!
#### Evan Phoenix and Adam Keys

[Video of event](https://www.youtube.com/watch?v=sn7prRGGp4Q)

Tags: Pair Programing, Fun
Recommended for: Everyone

Evan and Adam give play by play of a three-way pairing session with Aaron Patterson,
Mike Perham and Eileen Uchitelle. The three ping pong pair in a mostly lighthearted
session.

### How to Performance
#### Eileen M. Uchitelle [@eileencodes](https://twitter.com/eileencodes)

Tags: Measurement, Performance
Recommended for: Developers

Eileen talk her work to make Rails integration tests faster. She shares methodologies
for measuring performance. She give insights on what and how to measure.

### Building CLI Apps for Everyone
#### Terence Lee [@hone02](https://twitter.com/hone02)

Tags: CLI, mruby
Recommended for: Developers

Terence shares the story of the evolution of the Heroku toolbelt  from Ruby to
Go. The Ruby Heroku toolbest required Ruby to be installed to use which was less
than ideal. By switching to Go Heorku was able to distribute binaries that
anyone can use. Terence shares how this can also be done using mruby-cli.

### Ruby 2 Methodology
#### Akira Matsuda [@a_matsuda](https://twitter.com/a_matsuda)

[Video of talk](https://www.youtube.com/watch?v=UhMnFy3vNAU)

Tags: Amazing Presentation Tech, History, Collaboration
Recommended for: Developers

### Domo Arigato mruby Roboto
#### Yurie Yamane and Maysayoshi Takahashi

Tags: Robots, Making, mruby
Recommended for: Everyone

[Video of talk](https://www.youtube.com/watch?v=7qWZ5w5v7Eg)

### Keynote and Q&A: Matz
#### Yukihiro Matsumoto [@yukihiro_matz](https://twitter.com/yukihiro_matz)

Tags: Ruby 2.3, Ruby 3, Funny
Recommended for: Rubyist

[Video of talk](https://www.youtube.com/watch?v=LE0g2TUsJ4U)
