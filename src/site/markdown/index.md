#### Modern Ajax-based User Interface

![Modern Ajax-based User Interface](img/carousel-ui.png)

Pivot4J comes with a fully functional [sample application][analytics] which has 
modern, Ajax-based and intuitive user interface.

#### Build OLAP Client With Framework of Your Choice

![Build OLAP Client With Framework of Your Choice](img/carousel-frameworks.png)

Pivot4J features clean separation of UI and backend layers, so it does not require 
any specific UI toolkit to be used. Pivot4J allows you to build your own OLAP client 
with whatever UI framework you're mostly comfortable with.

#### Conditional Cell Formatting Support

![Conditional Cell Formatting Support](img/carousel-properties.png)

Say goodbye to those ugly 'style' definitions in your MDX statenent! With Pivot4J's 
flexible conditional formatting support, you can finally do away with such a bad 
practice as embedding formatting information in a query statement.

#### Non-MDX Aggregation Support

![Conditional Cell Formatting Support](img/carousel-aggregation.png)

Ever have manually edited MDX to do client side calculations and got frustrated when 
you they don't support drill down? Pivot4J can solve such problems with its non-MDX 
based aggregation support.

---

### About

**Pivot4J** provides a common [Java][java-site] API for OLAP servers which can be used 
to build an analytical service frontend with pivot style GUI. It aims to leverage mature 
but now discontinued [JPivot][jpivot-site] project's	codebase to make it a general purpose 
OLAP API library which is independent of any particular GUI implementation.

Pivot4J also provides a fully functional [OLAP analytics application][analytics] built 
on top of its core library, along with a [plugin][pentaho-plugin] for [Pentaho BI platform][pentaho-site] 
which can be installed directly from the marketplace.

[Read more...][about]

### Features

* Supports most of the original JPivot's features, like drill down, drill through, sort, and more.

* Supports any OLAP backend for which an [Olap4J][olap4j-site] driver implementation is available.

* [Mavenized][maven-site] project structure with flexible and easy to use API. 

* Clean separation of UI and backend, which enables you to build your own OLAP client with UI toolkit of your choice.

* Non-MDX based aggregation(a.k.a. 'visual total').

* Powerful formatting support based on MDX independent expression language.

### Pivot4J 0.8 is out!

After 4 months of development, *Pivot4J 0.8* is released on August 25, 2013 with many new features and 
bug fixes. Some of the highlights of the new release include :

* New report management UI.
	
* User configurable data sources and themes.

* Conditional formatting support(experimental).

* XMLA/SASS compatibility fixes.

* Updated Brazilian Portuguese translation, thanks to [IT4Biz][it4biz-site] and Professor Coruja Team.

For a full list of changes, please see the changelog [here][changelog].
	
### What's coming up next?

As we're in the process of restructuring the project, there won't be many new features for now. 
Some of the planned features for the next release (Pivot4J 0.9) include :

* Maven groupId and package change (*For developers*: Please read [this][0.9-changes] for details).

* New web site, based on [Maven Reflow skin][maven-skin-site].

* Basic charting support.

* Update to JSF 2.2 and [PrimeFaces][primefaces-site] 4.0 (Pivot4J Analytics).

* Code clean up and more integration test cases.

### Contact

If you have any question or suggestion for the project, please leave your message at [the support forum][forum-site].

And we also have an IRC channel at the Freenode network, **#pivot4j**.

<iframe allowtransparency="true" frameborder="0" scrolling="no" 
	src="http://platform.twitter.com/widgets/follow_button.html?screen_name=pivot4j" class="twitter-frame"></iframe>

[about]: ./about.html
[analytics]: ./analytics.html
[pentaho-plugin]: ./pentaho.html
[changelog]: ./changes-report.html
[0.9-changes]: https://t.co/s6Ct2mUXbL

[forum-site]: http://groups.google.com/d/forum/pivot4j-list
[java-site]: http://www.java.com
[maven-site]: http://maven.apache.org
[maven-skin-site]: http://github.com/andriusvelykis/reflow-maven-skin
[jpivot-site]: http://jpivot.sourceforge.net
[olap4j-site]: http://www.olap4j.org
[mondrian-site]: http://mondrian.pentaho.com
[pentaho-site]: http://community.pentaho.com/
[primefaces-site]: http://www.primefaces.org/
[it4biz-site]: http://www.it4biz.com.br