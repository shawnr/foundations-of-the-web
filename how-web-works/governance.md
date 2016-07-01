#Who Controls What

<p>Across the Internet and World Wide Web, individuals are connecting machines to the network and they don't require any permission to do so. Anyone can connect a new machine to the network, and anyone can purchase a domain name or be assigned an IP address. There are different groups that guide the creation of standards, and there are certain entities who manage the assignment of names and numbers. But there is no central authority in charge of the Internet.</p>
<h2>Network Governance</h2>
<p>Nobody actually "governs" the Internet. It is an open, freely available system controlled collectively by all of the individuals who connect machines to it. The practice of "<a href="http://en.wikipedia.org/wiki/Internet_governance">internet governance</a>" is a mixture of ad hoc negotiations, open standards developed by nonprofit organizations, and the low-level settings and standards administered by the <a href="https://www.icann.org/">Internet Corporation for Assigned Names and Numbers</a> (ICANN) and the US Government's Department of Commerce through the <a href="http://www.ntia.doc.gov/">National Telecommunications and Information Administration</a>&nbsp;(NTIA).&nbsp;</p>
<p>ICANN operates through an agreement with the NTIA to manage the master lists of domain names on the Internet, sets IP addresses, and determines application ports reserved for transport protocols on the Internet (such as HTTP). ICANN sets the technical specifications for the "<a href="https://whois.net">whois</a>" service, which is used to determine the ownership and authoritative name servers for a specific domain name.</p>
<h2>Domain Names</h2>
<p>The nuts and bolts of <a href="http://en.wikipedia.org/wiki/Domain_name">how domains work</a> is a complex system of decentralized information lookup and routing. <a href="http://www.verisigninc.com/en_US/domain-names/online/how-dns-works/index.xhtml">This webpage from Verisign</a> explains how an actual domain name lookup works, and it's pretty fascinating. But for the purpose of understanding how to work with domain names in the most usual cases, we don't need this level of technical understanding.</p>
<p>Although ICANN manages the base registry of domain names, other companies, called "registrars," are authorized by ICANN to sell domain names. These registrars must adhere to rules and guidelines published by ICANN. When you buy a domain name, the company you purchased the name from becomes the "<a href="http://en.wikipedia.org/wiki/Domain_name_registrar#Designated_registrar">designated registrar</a>" for that domain. You are listed as the owner, and possibly as one of the administrative or technical contacts (those roles may be held by somebody else, too -- such as your website's hosting service).</p>
<p>The registrar handles listing any domain names they control in their "<a href="http://en.wikipedia.org/wiki/Name_server">Domain Name Server</a>" (DNS). These listings of domain names are called "DNS records". The DNS records will be propagated to all of the other name servers on the Internet over time, and it can take a few days for servers in the most remote portions of the Internet to catch up with changes to DNS records. This is why when you register or change a domain it can take varying lengths of time for the domain to become available all over the world.</p>
<p>The registrar you use to control your domains is your choice, but this will be the organization that provides your interface for modifying how the domain works, creating subdomains, etc. You also use this registrar to configure information about how services other than the web interact with your domain, most notably your email configuration and addresses.</p>
<h2>Evaluating Websites</h2>
<p>In order to evaluate the reliability of a website or web-based service, it's necessary to use multiple methods to gather information. It's also helpful to have clear criteria about what you hope to gain from your evaluation. For example, are you hoping to use data or facts presented on the website in a report or plan? In that case, the veracity of information matters much more than the security of the service. However, if you are planning to use an API to pull data and facts into your own website, then you may be concerned about both the security of the site's infrastructure as well as the quality of information.</p>
<p>None of the information presented below is exhaustive. There are many, many ways to investigate and verify whether or not a site is what it pretends to be.&nbsp;</p>
<h3>Technical Evaluation</h3>
<p>In evaluating the technical reliability and origin of a site, it's helpful to use the following techniques.&nbsp;</p>
<ul>
<li><strong>HTTPS</strong><br />Most sites running serious services that allow for logging in or submitting any personal data are using HTTPS, which is the secure form of HTTP. This is crucial because it keeps user data secure from the client to the server, which has become standard practice over the past few years.</li>
<li><strong>Whois</strong><br />The primary way to find out who owns and controls a website is the whois service. You can find many sites online that allow you to do a whois lookup. <a href="https://whois.net">Whois.net</a> is a good one to start with.</li>
<li><strong>Domain Name Analysis</strong><br />Use the techniques previously discussed to analyze the domain name and determine if it comes from a more or less reliable source. A .gov or .edu site is likely to support high levels of reliability, but that's not always the case. And .com or .org addresses are available to anyone, so they cannot really be used to indicate the reliability of information or services.</li>
<li><strong>URL Analysis</strong><br />Use the techniques previously discussed to analyze the URL to determine if it seems to support the information architecture and functionality you see presented on the site. URLs on high quality sites should make sense and feel "right".</li>
</ul>
<h3>Content Evaluation</h3>
<p>Evaluating content is difficult, especially since in some cases (such as <a href="https://medium.com">Medium.com</a>) a single site hosts the work of multiple authors operating independently. Regardless, for each piece of content in a site, you can use the "<a href="http://libguides.csuchico.edu/content.php?pid=326243&amp;sid=2669613">CRAAP</a>" (<a href="http://www.csuchico.edu/lins/handouts/eval_websites.pdf">PDF</a>) method to evaluate it's relative reliability. Here is a summary of what to look for:</p>
<ul>
<li><strong>Currency</strong><br />How timely is the information? When was it originally published? Has it been maintained/updated?</li>
<li><strong>Relevance</strong><br />What is the audience for this information? Is this relevant to my needs?</li>
<li><strong>Authority</strong><br />Who is writing this? What are their credentials for writing? How do they back up their claims?</li>
<li><strong>Accuracy</strong><br />Can I assert that this is factually accurate? Are sources cited? Are their typos or errors in presentation that cause me to doubt the information?</li>
<li><strong>Purpose</strong><br />Why was this content created? Do authors make their bias or intention clear? Are there any unstated biases or opinions represented?</li>
</ul>
<h3>Reputation Evaluation</h3>
<p>In addition to evaluating the site itself, it's useful to evaluate how the site is perceived by others online. The way others discuss a site or service can be very enlightening when making an evaluation.</p>
<ul>
<li><strong>Who links to this site?</strong><br />Search in Google and Bing for references to the domain, site name, author name, etc.&nbsp;NOTE: You can use the <a href="http://moz.com/blog/google-link-command-busting-the-myths">Google Reverse Link</a> command (add "link:example.com" to your query) to get some idea of places linking to the domain in question, but be aware this command does not list every site linking to a domain.</li>
<li><strong>Who talks about this site?</strong><br />Search for the domain on Twitter, Facebook, Instagram, Vine, etc. See if anyone has bookmarked the domain on delicious.com and note the tags they've added. If you're evaluating a business look it up on Yelp or Foursquare. Leverage social media to see what others think about the site or service. Find the social media home for the business and check out the activity on their streams. Find out if the site, author, or topic is on Wikipedia and how the content there fits with the content you are evaluating.</li>
<li><strong>Who has rated this site?</strong><br />In many subject area domains there are listings of reputable sites. If you are looking at a potential service to use in web development, there are many known sites that specialize in providing comparison grids or evaluations of services and technologies. Some examples of these are <a href="https://www.djangopackages.com/">Django Packages</a>, <a href="http://jsdb.io">JSDB</a> and <a href="http://www.cmsreview.com/">CMS Review</a>.&nbsp;</li>
</ul>