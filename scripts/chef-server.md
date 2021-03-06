Show Date: Friday, 1 June 2012

Panel
====

* Kevin Smith, Director of Engineering [twitter](http://twitter.com/kevsmith), [github](https://github.com/kevsmith)
* Seth Falcon, Development Lead [twitter](http://twitter.com/sfalcon), [github](https://github.com/seth)
* Matt Ray [twitter](https://twitter.com/#!/mattray), [github](https://github.com/mattray)
* John Vincent, aka Lusis [twitter](https://twitter.com/#!/lusis), [github](https://github.com/lusis)
* Bryan Berry [github](http://github.com/bryanwb), [twitter](http://twitter.com/bryanwb), irc: bryanwb, blog: [devopsanywhere](http://devopsanywhere.blogspot.com)

Show Outline
============

* Chef server rewrite
* Open source, private, and hosted Chef server
* Erlang

Picks
* Kevin
  * [Paxos Made Moderately Complex](http://www.cs.cornell.edu/courses/cs7412/2011sp/paxos.pdf)
  * [Foundations of Multidimensional and Metric Data Structures](http://www.amazon.com/Foundations-Multidimensional-Structures-Kaufmann-Computer/dp/0123694469)
* Seth
  * git rerere mod
    * git config --global rerere.enabled 1
    * http://www.kernel.org/pub/software/scm/git/docs/v1.5.6/git-rerere.html
* Bryan
  * [Ilya Grigorik's blog](httP://igvita.com)
* lusis
  * Clojure 

* On the server-side Chef has undergone a lot of changes in that last
  several months. What motivated those changes and what are the changes?
* What are the different versions of Chef Server available? private
  chef, hosted chef, stay-at-home chef?
* What does private chef offer that the open-source Chef server does
  not? (multi-tenancy?)
* Why rewrite much of the backend in Erlang? Why not a more enterprise
  friendly language like java, Scala, or clojure?
* What database did u choose to replace CouchDB
* what changes happening in the Web UI?
* Why use Rails 3 for the Web UI and not just consolidate everything into Erlang?
* Do you still need Solr for search? Couldn't you just use tsearch in
  postgresql instead? That would mean one less component
* Will the current all ruby chef-server continue to be maintained by Opscode?
* What will the upgrade path look like for people running the
  open-source chef-server?
* Will Open-source chef-server ever get multi-tenancy?
* When will the new version of chef-server be open-sourced? and how
  much of it will be open-sourced?
* some listeners have expressed frustration that the current
  open-source chef-server isn't better supported. They point to a
  large number of open issues that don't seem to be receiving much
  attention from Opscode's engineering team. What do you say to that sentiment?
* will open-source Chef-server see maintenance love after the switch
  to Erlang/mysql?
* While I don't use the web gui very often, there are a few features I
  would love to see. When might we expect to see them?
   * dashboard showing last chef-client run
   * dashboard showing failed runs w/ stack-trace
* Do all the changes to chef-server impact chef-solo in any way? I would assume not, but guess it is possible.
* Now that you have improved the performance and memory management for
  chef-server, what's next for Chef-server? What kind of new features
  can we expect to see?
* In the DevOps Cafe interview, CB hinted about running analytics on
  the information collected by Chef, perhaps to predict hardware
  failures. Can you provide more details on this?
* What features would you like to see in the future?
* Will chef and chef-server always be locked into the model of running the chef-client periodically rather than actively asserting system state?
  Will it be able to evolve into a [next-gen configuration management tool](http://blog.lusis.org/blog/2012/05/24/configuration-drift-and-next-gen-cm/)?

CLOSE
=====

thanks to Eric Reeves for intro music
pls send ideas feedback to info@foodfightshow.org

Please take the time to rate us on itunes and to send your cookbook
news to info@foodfightshow.org

Follow [@foodfightshow](http://twitter.com/foodfightshow) on twitter.

Also, you can submit show ideas to our [github repo](https://github.com/foodfight/showz)

Until next time, Keep it Hot!
