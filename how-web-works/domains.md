#Domains and URLs

<p style="text-align: center;"><img src="https://i.imgur.com/cnyn8s3.png" alt="Ping results for google.com" width="640" height="243" /><br />Ping results for google.com</p>
<p>Although IP addresses are specific and unique, they are not very easy for humans to read. If somebody talks to you about the server located at&nbsp;173.194.33.38, you are unlikely to immediately recall whose server that is. However, if somebody mentions google.com (whose primary IP address is&nbsp;173.194.33.38), then you are likely to immediately understand what they mean.</p>
<p>The textual name we use to indicate domains is called a "domain name" and it is used to indicate a more human-friendly address for a server. Domain names can be pointed at any IP address by whoever controls the domain name registration. This is similar to how contacts in your phonebook work. When you add a contact to your phone, you enter their phone number, which is a lot like an IP address. If the phone rings and all you see is the number, then you're unlikely to recognize who is calling. So you also add a name to the contact (and maybe a bunch of other information). The name of your contact is akin to the domain name for a server. When the phone rings and you see that it's Uncle Bob calling, then you know immediately what to expect when you answer: You will be talking to Uncle Bob.</p>
<p>If Uncle Bob got a new phone with a new number, then you would change the number in your phonebook, but not the rest of the contact info. Similarly, if you wanted to change the server hosting your website, you could point your domain from one IP address to another, and then anybody who visits your domain will see content delivered from the new server.</p>
<h2>Reading Domain Names</h2>
<p>Example domain name: <strong>www.example.com</strong></p>
<table style="width: 100%; display: table;" border="0" cellspacing="4" cellpadding="4">
<tbody>
<tr>
<td style="text-align: center; width: 33%; background-color: #ccc;"><strong>Subdomain</strong></td>
<td style="text-align: center; width: 33%; background-color: #ccc; border-left: 1px dashed #333; border-right: 1px dashed #333;"><strong>Domain</strong></td>
<td style="text-align: center; width: 33%; background-color: #ccc;"><strong>Top-Level Domain</strong></td>
</tr>
<tr>
<td style="text-align: center; width: 33%; background-color: #e8f5fc;"><strong>www</strong></td>
<td style="text-align: center; width: 33%; background-color: #e8f5fc; border-left: 1px dashed #333; border-right: 1px dashed #333;"><strong>example</strong></td>
<td style="text-align: center; width: 33%; background-color: #e8f5fc;"><strong>com</strong></td>
</tr>
<tr>
<td style="text-align: center; background-color: #f2f2f2; padding: 10px;" valign="top">
<p style="text-align: left;">The subdomain is the most specific part of the address. It generally indicates the functions available at that subdomain. For example, the "www" subdomain generally indicates a webserver is present at that address. Other common subdomains include "mail" (email server) and "ftp" (file transfer server).</p>
</td>
<td style="text-align: left; background-color: #f2f2f2; padding: 10px; border-left: 1px dashed #333; border-right: 1px dashed #333;" valign="top">
<p>The domain is the name registered by the owner of the domain, and this indicates the "property" name for the domain. For example, all services found under google.com can be assumed to belong to Google, who owns the domain "google."&nbsp;</p>
</td>
<td style="text-align: left; background-color: #f2f2f2; padding: 10px;" valign="top">
<p>The top-level domain (or TLD as it is commonly called) indicates the larger categorization of the domain. These typically indicate either country (such as ".uk" or ".us") or another notion of purpose (such as ".org" or ".com"). Some TLDs have restrictions, such as ".edu" (only for educational institutions) or ".ch" (only for Swiss sites).</p>
</td>
</tr>
</tbody>
</table>
<p style="text-align: center;">&nbsp;</p>
<p>Domain names are structured in a standardized way so that they can easily be parsed and understood by machines who must route communications between nodes of the network. They can be read from right to left in order of most general to most specific: Top-level domain =&gt; domain =&gt; subdomain.&nbsp;</p>
<p>The domain is like the "city, state and country" in an address -- it gets us close to the data we want, but it usually doesn't specify the exact piece of information we want. We need a "street address" that tells us where our data lives. In order to find the unique location of a document or data object online, you need the object's <a href="http://en.wikipedia.org/wiki/Uniform_resource_locator">Uniform Resource Locator</a> (URL).&nbsp;</p>
<h2>Reading URLs</h2>
<p style="text-align: center;"><img src="http://i.imgur.com/vQqmQv2.png" alt="Youtube search for cute cats." width="640" height="295" /><br />Youtube search for cute cats</p>
<p style="text-align: left;">Take, for example, the URL in the screenshot above. It reads like an address that tells you how to get to this specific response from Youtube.com. Here is how we can break down this URL:</p>
<p style="text-align: left;">Example URL: <strong>https://www.youtube.com/results?search_query=cute+cats</strong></p>
<table style="width: 100%; display: table;" border="0" cellspacing="4" cellpadding="4">
<tbody>
<tr>
<td style="text-align: center; width: 15%; background-color: #ccc;"><strong>protocol</strong></td>
<td style="text-align: center; width: 25%; background-color: #ccc; border-left: 1px dashed #333; border-right: 1px dashed #333;"><strong>domain</strong></td>
<td style="text-align: center; width: 25%; background-color: #ccc; border-right: 1px dashed #333;"><strong>path</strong></td>
<td style="text-align: center; width: 35%; background-color: #ccc;"><strong>query string</strong></td>
</tr>
<tr>
<td style="text-align: center; width: 15%; background-color: #e8f5fc;"><strong>https://</strong></td>
<td style="text-align: center; width: 25%; background-color: #e8f5fc; border-left: 1px dashed #333; border-right: 1px dashed #333;"><strong>www.youtube.com</strong></td>
<td style="text-align: center; width: 25%; background-color: #e8f5fc; border-right: 1px dashed #333;"><strong>/results</strong></td>
<td style="text-align: center; width: 35%; background-color: #e8f5fc;"><strong>?search_query=cute+cats</strong></td>
</tr>
<tr>
<td style="text-align: center; background-color: #f2f2f2; padding: 10px;" valign="top">
<p style="text-align: left;">The protocol indicates the mechanism the browser used to contact the server. HTTPS indicates a Secure connection.</p>
</td>
<td style="text-align: left; background-color: #f2f2f2; padding: 10px; border-left: 1px dashed #333; border-right: 1px dashed #333;" valign="top">
<p>The domain name indicates the location of the server being contacted. &nbsp;</p>
</td>
<td style="text-align: center; background-color: #f2f2f2; padding: 10px; border-right: 1px dashed #333;" valign="top">
<p style="text-align: left;">The name "path" refers to the fact that web servers traditionally pointed to browsable file systems, so the "path" to the file or folder was needed to locate data.&nbsp;</p>
<p style="text-align: left;">In modern websites, the path is often a conceptual information representation and not necessarily tied to a file system.</p>
</td>
<td style="text-align: left; background-color: #f2f2f2; padding: 10px;" valign="top">
<p>Query strings generally indicate values that "configure" the server response. In this example, the value "search_query" is populated with "cute+cats". That value is passed to the search engine, and the results displayed change depending on the value of the "search_query" parameter.</p>
<p>&nbsp;</p>
</td>
</tr>
</tbody>
</table>
<p style="text-align: left;">&nbsp;</p>
<p style="text-align: left;">The URL indicates all of the information we need to get back to a specific response from the Web Server. That response is probably a web page or a data object that can be used by another application. The response should be consistent (a search for "cute cats" should always show me videos about cute cats). And the more I can pass it around by copying/pasting the URL, the more the content can spread and thrive.</p>
<h3 style="text-align: left;">Protocol</h3>
<p style="text-align: left;">In order to document the location of an object online, we being with the protocol. This indicates the method used by the client to contact the server. Many web browsers support multiple protocols. The most common protocols supported in web browsers are <a href="http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol">HTTP</a>, <a href="http://en.wikipedia.org/wiki/Https">HTTPS</a>, and <a href="http://en.wikipedia.org/wiki/Ftp">FTP</a>. Remember, these protocols provide the rules for communication used by clients and servers.</p>
<h3 style="text-align: left;">Domain</h3>
<p style="text-align: left;">As discussed above, the domain provides a human-friendly name for a specific server. Subdomains are often used to run specific applications or services, and domains are listed in a system called the Domain Name Server (DNS) so that different routers can discover what numeric IP address corresponds to the domain name being requested.</p>
<h3 style="text-align: left;">Path</h3>
<p style="text-align: left;">Paths provide the location of specific data objects. A data object might be a full web page, or just a blob of information in a structured format. Each data object exposed by a website or application requires a unique path to be located. In the example above, the path is simply "/results", which displays items found in a search query. This path will always render results from a search. Every search you perform on Youtube will lead you to this path in order to display the results.</p>
<p style="text-align: left;">Paths used to relate only to the file system of the web server. A path such as "/users/shawnr/index.html" may correspond to the index.html file inside shawnr's user directory. For simple websites which do not use any application to control the delivery of information, this is still true. You can always just put up a set of directories and files in order to transmit web pages. Each page will have a unique URL in your site, and a request to that URL will return the web page as a data object to the browser.</p>
<p style="text-align: left;">However, in modern web applications, it is unlikely that the path in the URL corresponds to a location on the server's disk drive. The path is probably a set of keywords that seeks to do two things:</p>
<ol>
<li>The path provides an information hierarchy that should be meaningful. Reading the path of a website should help users or fellow developers understand what this page is and "where" it is located in the hierarchy of the website/application.</li>
<li>The path relays information to the underlying application that the system requires to operate.&nbsp;</li>
</ol>
<p>For example, a blog may have a URL that looks like <a href="http://www.example.com/2014/03/15/greatest-headline-ever/">http://www.example.com/2014/03/15/greatest-headline-ever/</a>. That URL conveys a good deal of meaning. We can guess that the post was originally posted on March 15, 2014, and the headline is probably "Greatest Headline Ever".&nbsp;</p>
<h3 style="text-align: left;">Query String&nbsp;</h3>
<p><a href="http://en.wikipedia.org/wiki/Query_string">Query strings</a> are the variable values that come after the question mark in a URL. The question mark denotes the beginning of the query string. Query strings are intended to provide a way to send data to the web server that does not fit into the hierarchical organization of the site. In the best cases, this usually means that query strings contain search terms and pagination details.&nbsp;</p>
<p>When submitting a search query to a web server there are often many pieces of information used to hone your results. You might search for a term like "fiddles", but you might also have selected a media type filter for "images" and a size filter for "large". Furthermore, you may be viewing the third page of results, contain results numbered 60-79. All of this information is likely to be contained in a query string. An imaginary URL with a query string like the one described might look like this:</p>
<p><strong>http://www.example.com/results?term=fiddles&amp;type=image&amp;size=large&amp;page=3&amp;per_page=20</strong></p>
<p>This kind of query string still provides a direct link to a permanent location, but it's important to realize that in the case of dynamic applications the data returned might be different each time you visit the page. In this example, the web server would pass five variables to the web application as part of the request: term, type, size, page and per_page.</p>
<p>Note that query strings begin with a question mark (?). Query string variables are separated by an ampersand (&amp;) and the equals sign is indicated to set the value of the variable.</p>