# A guide to sustainability models for research software projects.

*"How can we find funding for our open source project?"*

First things first: This started as a fork from https://github.com/nayafia/lemonade-stand. [@nayafia](https://github.com/nayafia) wanted to focus on how people fund their work on open source projects, and not how the projects themselves are sustained, which she thought was out of scope for her document (see https://github.com/nayafia/lemonade-stand/issues/1), so I've created this instead.

A project often starts with a bright idea and an initial commitment of volunteer time, or perhaps, a fixed term grant.  But what happens after that initial activity?  How can the project continue to sustain itself?  (We define sustainability as the capacity to endure.  Software is sustainable if it will continue to be available in the future, on new platforms, and meeting new needs.  [This is from slide 23 of http://www.slideshare.net/danielskatz/scientific-software-challenges-and-community-responses, though it may have been taken from somewhere else earlier - if you know where, please fix this.])

The intent below is to list how projects do this — support themselves over time.  Each funding category should ideally link to several real examples, and when possible, to a useful article or page instead of just a homepage.

The categories are not mutually exclusive. For example, a project might have a foundation but also use crowdfunding to raise money. Another project might provide services and also have a donation button. Etc. The purpose of this guide is to provide an exhaustive list of all the ways a project can survive, so that your project can figure out what works best for you.

[probably drop this sentence later] In addition to suggesting ways that individual developers can get paid for their work, most of these categories are useful for projects that want to find funding for their project/team.


---


# Table of Contents
1. [Volunteers](#volunteers)
2. [Donation button](#donation-button)
3. [Crowdfunding (one-time)](#crowdfunding-one-time)
4. [Crowdfunding (recurring)](#crowdfunding-recurring)
5. [Books and merchandise](#books-and-merchandise)
6. [Advertising & sponsorships](#advertising--sponsorships)
7. [Industry support](#industry-support)
8. [Grants](#grants)
9. [Consulting & services](#consulting--services)
10. [SaaS](#saas)
11. [Dual license](#dual-license)
12. [Open core](#open-core)
13. [Foundations & consortiums](#foundations--consortiums)
14. [Venture capital](#venture-capital)
15. [Trademark licensing & Franchising](#trademark-licensing--franchising)

APPENDIX: [Contributing to this guide](#contributing-to-this-guide) // [License & attribution](#license-and-attribution)  

**"personal effort" notes when a funding effort was led by an individual, not a project*

## Volunteers
*Get people to volunteer their time to your project*

#### Pros
* A good community can become self-sustaining
* Having a large, diverse set of developers available makes it more likely that one might work on a given issue

####Cons
* Ethical concerns (ex., see [The Ethics of Unpaid Labor and the OSS Community](https://www.ashedryden.com/blog/the-ethics-of-unpaid-labor-and-the-oss-community) by Ashe Dryden)
* Organizing large numbers of volunteers can be difficult

####Case Studies
* [Linux Kernel](https://www.kernel.org)
* [Mozilla Firefox](https://developer.mozilla.org/en-US/docs/MDN/Community)
* [Apache Open Office](https://openoffice.apache.org/get-involved.html)
* [yt](http://yt-project.org)

## Donation button
*Stick a donation button on your project's site. Stripe and PayPal are examples of services a project can use to accept donations.*

#### Pros
* Few strings attached
* Little work involved: "set it and forget it"

####Cons
* Usually not much money unless you have dedicated fundraising efforts
* Need a legal entity to donate to (ex. [SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com), [NumFOCUS](http://www.numfocus.org) are fiscal sponsors for this purpose). Harder for individuals or international donations to manage
* Sometimes not clear who “deserves” money in a project or to what efforts it gets distributed
* Likelihood of success related to number of users, not importance of software

####Case Studies
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)

##Crowdfunding (one-time)
*If a project has a specific idea it wants to implement (rather than ongoing project work), a one-time crowdfunding campaign can help raise the needed funds. Both individuals and companies might be willing to donate to the campaign.*

####Pros
* Few strings attached
* Can be easy to legally manage via, ex. [Kickstarter](https://kickstarter.com/)

####Cons
* Lots of work involved to market campaign
* Usually has to be tied to concrete outcome, perks
* Usually not that much money (~$50K for one time)
* Companies not always comfortable donating to campaigns

####Case Studies
* [Michal Papis + Rvm (personal effort)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (personal effort)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (personal effort)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](http://poststatus.com/kickstarter-open-source-project/)

##Crowdfunding (recurring)
*If you'd like to fund ongoing project work, you can set up a recurring crowdfunding campaign, with a monthly or annual financial commitment that renews indefinitely (or until the donor cancels). Those who use your project regularly (including both individuals and companies) might be willing to fund your work.*

####Pros
* Few strings attached
* Can be easier for an individual to legally manage via, ex. [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/), [OpenCollective](https://opencollective.com)

####Cons
* Harder to get commitments to recurring donations (often requires preexisting brand/reputation)
* Harder to explain concrete outcomes, perks that come with recurring donations
* Usually not that much money (~$1-4K monthly)
* Companies not always comfortable donating to campaigns

####Case Studies
* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (personal effort)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)

##Books and merchandise
*If you are an expert in a domain that other people might find useful to learn about, you could write and sell a book or series of books. You can find a publisher (like O'Reilly) or self-publish. In addition to selling books, some projects sell merchandise (ex. shirts, hoodies) to support their work.*

####Pros
* Outcome not tied to project work itself, so you retain creative freedom
* Can serve as marketing for the project itself
* Can be recurring source of revenue after initial development

####Cons
* Often not a significant source of revenue
* Can distract from core development of project
* Merchandise can have upfront costs

####Case Studies
* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (personal effort)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (personal effort)](http://www.poodr.com/)
* [Kyle Simpson + You Don't Know JS (personal effort)](https://github.com/getify/You-Dont-Know-JS)
* [CocoaPods (fundraising for charity)](https://cocoapods.org/socks)

##Advertising & sponsorships
*If your project has a large audience, you can sell sponsorships to advertisers who might want to reach them. You probably have a very targeted audience (ex. if you have a Python project, you can assume your audience is likely people who are technically familiar with Python), so use that to your advantage.*

####Pros
* Business model aligned with something people are willing to pay for

####Cons
* Need large enough audience to justify sponsorships
* Need to manage trust and transparency with user base (ex. no tracking)
* Can be a lot of work to find and manage clients

####Case Studies
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)

##Industry support
*Companies sometimes hire individuals to do open source work to support particular projects. Find a company that uses your project, and determine something the project wants to do that the company is willing to put work into*

####Pros
* Taps into those who have resources (i.e. companies)
* Can be well-aligned with company needs

####Cons
* Usually involves “getting lucky”: no clear, repeatable path to finding this arrangement
* Project already needs to be well-known and used
* Governance issues, company could have undue influence over project
* Can affect project dynamics + balance

####Case Studies
* 

##Grants
*Grants are effectively large donations that do not require repayment. Oftentimes the grantmaker receives other benefits from giving you the grant, such as access to you, demonstration of impact, a report of your work, or tax benefits.*

*Grants can come from many places, including companies, software foundations, philanthropic foundations, and the government. The technical and legal aspects of a grant vary greatly depending on where it comes from. For example, a company might give you a "grant" but legally treat it as a consulting invoice. A philanthropic foundation can only make grants to nonprofits, so you would need to be a nonprofit yourself, or (more commonly) find a nonprofit to sponsor you. If you're unfamiliar with grants, the best way to understand how grants work is to talk to someone who has received one before. Some examples of grant recipients are listed below.*

####Pros
* Fewer strings attached
* Guaranteed money can help project focus for an unbroken period of time
* Gives project room to breathe and experiment

####Cons
* There aren’t many software-related grantmakers (philanthropic, gov’t, corporate)
* Grants are finite. Still need to find sustainability beyond the life of a grant

####Case Studies
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)

##Consulting & services
*A project can offer consulting & services around the project itself. For example, a client might pay you to implement the project for them, build something custom, or train them on how to use it.*

####Pros
* Business model aligned with something people are willing to pay for

####Cons
* Consulting requires human power, doesn’t scale well (except for rare outliers)
* Business needs can distract from writing code or other tasks related to the project itself
* Can be at odds with making software simple to use
* Project needs to be sufficiently popular that people are willing to pay for related services

####Case Studies
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

##SaaS
*SaaS means [Software as a Service](https://en.wikipedia.org/wiki/Software_as_a_service). In this model, the codebase itself is open source, but you might offer additional paid services that make it easier for people to use your project. One common example of a paid service is charging for hosting.*

####Pros
* Can build community around open project and make money off of services for hosting
* Allows open source project to focus on users and as needs grow to help enterprises adopt the project
* Can scale by number of users

####Cons
* Often means the hosting needs to be cheaper than hiring a dev to run the project for you.
* “Two tiers” of product support can make free users unhappy

####Case Studies
* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Gitlab](https://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)

##Dual License
*Sometimes, projects offer an identical codebase with two different licenses: one that is commercially-friendly, and one that is less so (ex. GPL). The latter is free for anyone to use, but companies pay for the commercial license in order to have legal peace of mind.*

####Pros
* Business model aligned with something people are willing to pay for
* Can scale well if successful

####Cons
* Can be at odds with making software freely accessible
* Project needs to be big enough that customer need exists

####Case Studies
* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)

##Open core
*Under an [open core](https://en.wikipedia.org/wiki/Open_core) model, some aspects of the project are free, but other features are proprietary and available only to paid users. Usually this works when there is enterprise demand for the project.*

####Pros
* Business model aligned with something people are willing to pay for
* Can scale well if successful

####Cons
* Need to have something you can charge for (which means making certain features exclusive)
* Can be at odds with making software freely accessible
* “Two tiers” of product support can make free users unhappy

####Case Studies
* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)

##Foundations & consortiums
*A [foundation](https://en.wikipedia.org/wiki/Foundation_(nonprofit)) is a legal entity that can accept and/or disburse donations. Because their purpose is not to make profits, they can be a great choice to signal neutrality and steward a project. In the US, foundations are either 501(c)(3) (nonprofit) or 501(c)(6) (trade consortium). Many software foundations are 501(c)(6) because 501(c)(3)s require demonstrating a charitable purpose, which can be more difficult in software.*

####Pros
* Neutrality. Foundation protects the code and helps steward community
* Influence distributed across multiple donors
* Can legitimize project, companies might feel more comfortable giving to foundations than individuals

####Cons
* Only really worth it for big projects
* Difficult to set up for IRS reasons (many do 501(c)(6) instead of 501(c)(3)), restrictions on what you can do
* Requires serious community effort and diverse skills (you still need to fundraise after setting up the entity!)

####Case Studies
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)

##Venture capital
*Venture capital is a form of funding for high growth businesses. Unlike a bank loan or other forms of debt financing, venture capitaists take equity (a percent ownership in your business) in exchange for funding. The tradeoff is that unlike taking out a loan, you don't have to repay your creditors if your business tanks. If you do succeed, however, you should expect to return capital to your investor at a multiple.*

*Venture capital is "high risk high reward": VCs are more risk tolerant than, say, a bank, but they also expect a large payoff if you are successful. If you plan on raising venture capital, you should set up a business entity structured as a C Corp, preferably Delaware. If you're unfamiliar with the venture capital process, the best place to start is by reaching out to similar founders who have successfully raised venture.*

####Pros
* Institutional support can be helpful for growing a business
* Large amounts of capital available

####Cons
* Venture capital comes with expectations of an exit (i.e. returning the money to investors at a multiple). History suggests this is structurally difficult to achieve for open source businesses
* Venture capital can change motivations and distract from priorities

####Case Studies
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)

##Trademark licensing & Franchising
*If a FOSS project has a well-known name and large user community, it can potentially capitalize on its trademark as a form of intellectual property to license out to franchises that provide support or hardware appliances that use the software.*

####Pros
* It works in places where SaaS may not.
* It requires little upfront capital to deploy this model.

####Cons
* This is not a solution for software with small communities or a name
that is not well-known.
* There has to be profitability in building appliances or franchises for
support and training. This makes it a better fit for software that is
complex to setup and maintain.

####Case Studies
* [Moodle] (https://moodle.com/trademarks/)
* [Red Hat] (https://www.redhat.com/en/about/trademark-guidelines-and-policies)

---

### Contributing to this guide
As with [the original](https://github.com/nayafia/lemonade-stand) from [@nayafia](https://github.com/nayafia), this guide welcomes changes and edits.  If something is factually incorrect (especially with a case study example), your edits would be great.  Also, if there's a category that's missing, please add it.

### License and attribution
This guide is available under the Creative Commons CC0 1.0 License, meaning you are free to use it for any purpose, commercial or non-commercial, without any attribution back to me (public domain).
