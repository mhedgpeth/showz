Show Date:  4 November 2013

Panel<a name="panel"></a>
-----

* Al Tobey, Open Source Mechanic at Datastax [github](https://github.com/tobert), [twitter](https://twitter.com/AlTobey)
* Bryan Berry [github](http://github.com/bryanwb), [twitter](http://twitter.com/bryanwb), irc: bryanwb, blog: [devopsanywhere](http://devopsanywhere.blogspot.com)
* Mike Fiedler [github](http://github.com/miketheman), [twitter](http://twitter.com/mikefiedler), [blog](http://www.miketheman.net)

[Youtube Video](http://www.youtube.com/watch?v=2Iz2ydIrPA8)


Outline/Questions
-----------------
* all about Al
  * how did you get started in the industry?
  * what did u do at ooyala?
  * what's your role at datastax?
  * you call yourself a "heuristician", what does that mean? Does that
fit in w/ Brendan Gregg's USE method at all?
  * You recommend "Testing in Production", why?
  * What is the OODA loop? do you try to document your findings during it?
  * Al's [talk](http://www.youtube.com/watch?v=_IL1u1IIRhc) on optimizing Cassandra
* Cassandra
  * How is cassandra better than riak?
  * How is riak better than cassandra?
  * Cassandra is a freaking awesome, battle-tested database. However, a large portion of devs seem to
choose either mongodb or old-school rdbms's when designing a new app, at least an MVP. Why is this? are
you working to change this?
* JVM stuff
  * cassandra uses the oracle JDK, why not openjdk? would seem to be much easier to bundle together w/ c*
  * One of the biggest pain points for managing a java app is tuning the heap size.
cassandra stores a lot of stuff off heap, why don't more java-based projects do this? like zookeeper
or tomcat.
  * Since there are so many java-bases apps, esp in the hadoop space, why is managing the heap still such a pain?
Are there any open-source initiatives towards a "pauseless gc"?
* Linux
  * You recommend testing out new filesystems in production, at least for cassandra, isn't that crazy?
  * Arent' ext4 and xfs good enough? Why should we consider newer filesystems like zfs on linux or btrfs?
  * why store bits on disk compressed?
  * is btrfs stable enough to use in prod?
  * What do you use for your desktop/laptop OS? *gasp* linux? why not mac os? should others consider
linux? what are the pluses, minuses? what's your setup?
  * what are your thoughts on systemd? is it the way forward?
  * You ran custom kernels at Ooyala? why? should more of us consider doing that?
  * explain what cgroups are and how you might use them
  * talk about different i/o schedulers (as most aren't even aware of their existence)
  * what linux tools should everyone use? (like htop)
* Learning
  * Golang is super hip in the ops world right now, what has your experience been w/ it?
  * W/ so many big distributed apps in java these days, do u recommend ops folks learn java or
just learn golang?
  * what else are you excited about? serf? raft?

Picks<a name="picks"></a>
-----

#### Bryan

<<<<<<< HEAD
#### lusis

#### Nathen
=======
* Remapping the right option key on the Macbook to be a Control key
* M-f, M-b, M-d, M-del shortcuts in the shell, see the [Emacs Readline Cheatsheet](http://www.catonmat.net/download/readline-emacs-editing-mode-cheat-sheet.pdf)

#### Al 

* [Vibram shoes](http://www.vibramfivefingers.com/index.htm)
* [Serfdom](serfdom.io)

#### Mike

* [Basil Polenta with Poached egg and lemon roasted brussel sprouts](http://www.cuculinary.com/2013/03/basil-polenta-with-poached-egg-and-lemon-roasted-brussels-sprouts/)
* [Ruby Monk Ruby Tutorials](http://rubymonk.com/)


>>>>>>> 158fc6f... add picks



CLOSE
-----

Make sure to subscribe to the [Foodfight Weekly Newsletter](http://bit.ly/ffsmail) and send your cookbook
news to info@foodfightshow.org

Follow [@foodfightshow](http://twitter.com/foodfightshow) on twitter.

Also, you can submit show ideas to our [github repo](https://github.com/foodfight/showz)



Download
--------
