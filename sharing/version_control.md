# Version Control

<p>Although many web users are familiar with the idea of editing a page using a "Content Management System" such as Wikipedia, fewer users are familiar with the notion of conscientious version control. Most digital content production involves the use of some form of version control. Web development is no exception. This page aims to provide an introduction to the concept of version control and how it fits into a production process.</p>
<h2>What is "version control"?</h2>
{% video %}https://vimeo.com/41027679{% endvideo %}

<p>The video above does a good job explaining the core concepts of version control software. The core concept is something most people can connect with: You want to keep a history of versions of your files so that you can go back to any previous version. We often name files with a date or number such as "v1" so we can keep an old version in backup. Many applications, such as Google Docs and Apple's Time Machine, have added historical file versioning to specific applications. Users appreciate the security of having "backups".</p>
<p>However, that sort of historical file versioning is inadequate for enabling real collaboration. In order to truly collaborate on a document it's important that we can work simultaneously and then combine our respective changes. In version control language, we need to be able to create a "branch" from the "trunk" timeline for a given file, make edits, and then "merge" our "branch" changes back to the main "trunk". Represented visually, this is basically what that looks like:</p>
<p><img src="http://upload.wikimedia.org/wikipedia/commons/4/4e/Subversion_project_visualization.svg" alt="" width="815" height="210" /></p>
<p>In order to facilitate the branching and merging, it's important for a version control software package to handle creating "diffs" of files. A "diff" is a representation of the difference between one file and another. Once the software can tell the difference, it can often perform a "merge", which allows work in one branch to be synthesized into another branch. This last step of allowing the diff and merge actions is crucial to enabling collaboration. And when changes are in "conflict" the diff and merge tools are useful for helping to resolve those conflicts. Users can be guided to make easy "this or that" choices to resolve conflicts.</p>
<h3>Additional resources for learning about version control in general:</h3>
<ul>
<li><a href="http://betterexplained.com/articles/a-visual-guide-to-version-control/">Illustrated guide to version control</a></li>
<li><a href="http://git-scm.com/book/en/Getting-Started-About-Version-Control">Getting Started With Git: About Version Control</a></li>
<li><a href="http://chronicle.com/blogs/profhacker/a-gentle-introduction-to-version-control/23064">A Gentle Introduction to Version Control</a></li>
</ul>
<h2>How version control enhances collaboration and production</h2>
<p>With version control software in place, we can now work on a shared "repository" of code. To make a change, you create a branch, make edits, and then merge your branch back into the codebase. All of the other team members can do the same thing, and as you move forward you are able to effectively combine work. The cycle of collaboration, known as a "workflow", is partly dependent on the vcs technology chosen by the team, and partly dependent on the team's own culture of collaboration.&nbsp;</p>
<p>Version control does a lot to enhance the individual maker-to-maker collaboration of teams. Without version control, it would be impossible to have everyone working on the same files at the same time. This is a major boon to productivity and allows us to build much larger projects than would otherwise be possible. But there are other benefits to version control.</p>
<p>Things version control make possible/easier:</p>
<ul>
<li><strong>Continuous Integration</strong><br />Continuous integration is the concept that you should always be combining in-progress pieces of code and testing them. With version control in place, it becomes easy to trigger builds of a site or project after code is updated. This allows for rapid testing and notification if something has broken in the product.</li>
<li><strong>Simplified Deployments</strong><br />Getting files from one place to another is often a chore, especially when dealing with large numbers of individual files or directories. Version control software packages projects and transmits them in different ways, allowing for easy transfer of files from one location to another, and easy updates to keep locations in sync.</li>
<li><strong>Simultaneous Development</strong><br />Developers, designers and other makers on a team can contribute to all the different parts of the project at the same time. Changes can be merged together easily, and conflicts can be resolved with minimal effort and no data loss. The "branch-edit-merge" cycle enables excellent productivity.</li>
</ul>
<p>With all these capabilities in place, it becomes possible to consider workflows and production cultures that value behaviors such as performing multiple deployments each day. This is something many sites and services do and we never realize it is happening. If we can constantly be developing new things, and those things are being continuously integrated into the product and tested to make sure they don't break the old things, then we can consider deploying new features every day. And if our deployment process is so simple that we can easily do it multiple times per day, then why not deploy new features as soon as they are ready?</p>
<p>Once we've gone that far, then it becomes a daily chore to gather feedback on the day's new features and suggest improvements and changes to keep enhancing the website or product. Once that is happening, then you have a full-blown contemporary web production workflow. Congrats! And to think it all started with simple version control...</p>