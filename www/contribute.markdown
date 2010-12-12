---
layout: main
title: Contributing to JRuby
---
# Contributing to JRuby
  
JRuby depends on community contributions to survive. Here's how you can get involved:

**Get the Source** - The JRuby source is stored in our Git repository at JRuby.org and mirrored at GitHub.

- **Browse**: [**JRuby.org**](http://www.jruby.org/git?p=jruby.git;a=summary)&nbsp;|&nbsp;[**GitHub**](http://github.com/jruby/jruby)
- **Checkout**

      git clone git://jruby.org/jruby.git
      git clone http://jruby.org/repo/jruby.git
      git clone git://github.com/jruby/jruby.git
      git clone http://github.com/jruby/jruby.git

*Need [Git help](http://git-scm.com/)? It's ok, we're not Git experts either.*

**Dependencies** - In order to build JRuby, you'll need a recent JDK (Java5 or higher), and <a href="http://ant.apache.org/">Apache Ant</a> 1.7.0 or higher.

**Build JRuby** - Once you've checked out the source, you just need to run `ant` or `ant jar` to build. To run our test suite, you need to put JRuby's `bin` folder at your `$PATH` environment.

      ant
      ant jar
      ant test

**Report Bugs** - Our bug tracker uses Atlassian JIRA. Please report anything you think is a bug! Performance problems are considered bugs, so please report those too.

- **Bug Tracker**: [**Browse**]({{ site.urls.jira }})

**Fix Bugs** - We'd love it if you help triage or fix open bugs. We've created a [**HelpWanted**][helpwanted] section of the bug tracker where we appreciate all the help we can get!

- **HelpWanted**: [Browse][helpwanted]

**Fix the wiki** - We also depend on community contributions and edits to keep our documentation informative and relevant. If you have a useful FAQ or walkthrough or article, please add it to the wiki. And we welcome anyone who wants to help reorganize or edit existing content.

- **Wiki**: [**Browse**]({{ site.urls.wiki }})

**Fix the website** - Our website source code is publicly available, and we graciously accept pull requests!

- **Website**: [**Browse**](http://github.com/jruby/jruby.github.com) &nbsp;|&nbsp;[**Checkout**](git://github.com/jruby/jruby.github.com.git)

[helpwanted]: http://bit.ly/jruby-help-wanted
