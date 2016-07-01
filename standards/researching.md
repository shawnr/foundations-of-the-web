#Researching Best Practices and Standards

<p>How do you figure out what to do to approach a problem? How do you know that your idea for a solution is not missing something obvious? How do you confidently tell your users and stakeholders that what you've built is as good as this sort of thing is likely to get these days?</p>
<p>The answer to all these questions is: Best Practices and Standards.</p>
<p>If you've done your homework and you have figured out the best practices and standards that apply to the work you're doing, then you can reflect on your work to see where you are meeting, exceeding, or purposefully deviating from established best practices or defined standards.</p>
<p>And realize that working in web development means having a somewhat intimate relationship with the development of these standards. Large groups of very talented developers are building new features that will become standardized over time, and although the official approval process can be very, very lengthy, the actual implementation of a new standard may well precede actual adoption and ratification.</p>
<p>So, how do we go about figuring things out?</p>
<h2>Tips for Researching Best Practices and Standards</h2>
<p>There is no single way to discover that you're "doing it right" or that you have not overlooked some crucial details in planning a specific feature or component. But if you follow some basic suggestions, then you can have an idea that you're probably not forgetting anything hugely crucial. Ultimately you'll have to get validation by sharing your approach with your peers, whether colleagues you work with or developers you interact with in the broader developer community.</p>
<h3>Start with the big stuff</h3>
<p>Make sure you're familiar with the basic standards set forth by the W3C. It's important to at least know which ones exist, and although it may be impossible to have exhaustive familiarity with the standards documents, it's helpful to have at least a few standards that you're familiar with. Obviously <a href="http://www.w3.org/standards/webdesign/htmlcss">HTML, CSS</a>, <a href="http://www.w3.org/standards/webdesign/script">Javascript</a> and <a href="http://www.w3.org/standards/webdesign/accessibility">Accessibility</a> are very useful standards for web developers to know about.&nbsp;</p>
<p>You might also be using development tools or technologies that require compliance with specific standards. For example, if you are working with a REST-based API then it would be helpful to be aware of the <a href="http://www.w3.org/standards/webdesign/script">Javascript Web API Standards</a>. You want to be aware of how things are generally working together when working with a given set of technology tools (often called a "stack" in web terms).</p>
<p>If you're in an educational, non-profit (or otherwise grant-based), or government organization then Accessibility may also be a legal standard you must meet. The Section 508 amendment to the Rehabilitation Act dictates a level of government accessibility compliance that is enforced for most projects making use of government funds. It's helpful to be aware of standards in your specific domain.</p>
<p>Major standards-making organizations in the field of web/software development:</p>
<ul>
<li><a href="http://w3.org">http://w3.org</a>&nbsp;</li>
<li><a href="http://www.iso.org/">http://www.iso.org/</a></li>
<li><a href="https://www.pcisecuritystandards.org/">https://www.pcisecuritystandards.org/</a>&nbsp;<a href="http://www.iso.org/"></a><a href="http://www.iso.org/"></a></li>
</ul>
<p>Major non-W3C standards you should know about:</p>
<ul>
<li><a href="http://www.coppa.org/">Children's Online Privacy Protection Act</a> (COPPA)</li>
<li><a href="http://www.business.ftc.gov/documents/bus61-can-spam-act-compliance-guide-business">CAN-SPAM Act</a></li>
<li><a href="http://www.section508.gov/">http://www.section508.gov/</a></li>
<li><a href="http://www2.ed.gov/policy/gen/guid/fpco/ferpa/index.html">Family Educational Rights and Privacy Act</a> (FERPA) (some <a href="http://nces.ed.gov/pubs2005/tech_suite/app_C.asp">guidelines for educational website developers</a> can be found here)</li>
</ul>
<p>Keep in mind that this list is very US-centric. If you are developing websites for organizations based in other countries, they may have their own governmental regulations and standards that apply. (For example, in the European Union any website that uses cookies must disclose that directly to their users, which is why if you visit a European website you will usually see a pop-up alerting you to the fact that the site makes use of cookies. This is known as <a href="http://www.cookielaw.org/the-cookie-law/">"The Cookie Law"</a> and has been in place since 2011. American sites don't need to alert users to their usage of cookies, although most US-based sites describe how cookies are used in their Privacy Policies and Terms of Service where relevant.)</p>
<h3>Keep up with current events</h3>
<p>There are many outlets covering news for web developers and blogs from developers who share their immense knowledge on a regular basis. Sites come along that track specific packages or standards, and others maintain a broad-based coverage of new standard development and support. These sites are very valuable and often write articles comparing the pros and cons of different techniques. And let's face it, the source documents are not easy or engaging to read. For many uses, it's handier to have a more accessible explanation of standards and best practices.</p>
<p>Stuff your feed reader with some of these sites, and then consult them when you're working through problems. Even when approaching problems you have solved before, it's worth it to consult the web for new ideas about how to improve on previous versions. Taking the opportunity to evolve our approach to similar problems over time is part of what allows the web to grow so dynamically.</p>
<p>Here are some good sites to check for information about standards, best practices and general evolution of technique:</p>
<ul>
<li><a href="http://www.html5rocks.com/">http://www.html5rocks.com/</a></li>
<li><a href="http://css-tricks.com/">http://css-tricks.com/</a>&nbsp;</li>
<li><a href="http://alistapart.com/">http://alistapart.com/</a>&nbsp;</li>
<li><a href="https://news.ycombinator.com">https://news.ycombinator.com</a>&nbsp;</li>
</ul>
<h3>Doublecheck technical requirements</h3>
<p>Before settling in on a single approach, make sure you've done your homework. Did an article convince you that the latest CSS3 technique would be supported back to IE8? That probably wasn't true. Use tools to doublecheck capabilities and dependencies. If you identify a problem with a target technology combination, then at least you can address it directly rather than having it crop up as a bug in the middle of development.</p>
<p>Here are some helpful tools/sites for checking requirements and capabilities:</p>
<ul>
<li><a href="http://caniuse.com/">http://caniuse.com/</a></li>
<li><a href="http://html5readiness.com/">http://html5readiness.com/</a></li>
<li><a href="http://wave.webaim.org/">http://wave.webaim.org/</a></li>
<li><a href="https://saucelabs.com/">https://saucelabs.com/</a>&nbsp;</li>
</ul>