# OA-Assessing-Accessibility
A project to provide tools making it easy for people (authors, editors, publishers, readers, librarians) to assess the accessibility of a articles cited in a scholarly article.

There are several use-cases where it is desirable to know which references in a list of citations refer to articles that can be found, in full-text, on the Internet without having to pass through a paywall. 

This project focuses on the author of a new article and assumes that the author has crafted their article either in Word or with the assistence of a citation manager such as Zotero.  If the author (as most do) supports the mission of having the scholarly literature in their field be open (available to scholars anywhere in the world without any paywall or registration barriers) then they might like to be able to assess which of their referenced articles are, in fact, available on the open web.

There are two means by which a referenced article might be available on the open web, namely via the "gold" path or the "green" path. Gold Open Access articles will be available from a publisher's website for free access immediately upon publication.  On the "green" path the publisher has acknoledged that the author is within their rights to share a version of their article via an institutional or subject-wide repository, or a personal or departmental website.  79% of all scholarly publishers, including all of the major ones give blanket permission for authors to share a verion of their articles freely. The site http://www.sherpa.ac.uk/romeo has record of which journals and publishers allow such sharing.  

A good percentage of scholars never get around to sharing their articles in a place that they can be found. However, if a new author is about to reference a set of articles and could easily determine which of them could be shared but hasn't been, then they could, possibly, e-mail those authors and encourage them to share their articles.  

The site http://dissem.in has open source code which already checks an article citation with the Sherpa/Romeo database to determine whether or not the publisher has allowed the author to share a version of that article.  Some use of that code may be an important part of this project. 

Google Scholar is often used by researchers to find articles and it can usually find "green" versions of articles in instituational repositories, subject repositories, author websites and places like academia.edu or ResearchGate.   However, as I understand it, Google Scholar does not have an API and it detects and prevents screen-scraping.  

One part of this project will be to explore some of the other search engines to see if they have APIs or allow screen scraping and to determine how effective they are at finding articles given the information about that article that you might have from a citation.

