# OdinProject

# -----------------------

# Knowledge Check Answers

# -----------------------

# How Does the Web Work?

What is a web server?

-- A web server is the hardware and/or software that responds to requests from clients on the world wide web.

What is a network?

-- A network is a collection of computers or other devices that are connected together and can communicate with one another. This doesn't require the internet, as seen with Local Area Networks (LAN).

What is the internet?

-- It is a network of networks. Modems from ISPs connect computer networks to other networks so that they can communicate with eachother.

What is an IP address?

-- An IP address is a unique address which identifies the computer in a network. IP stands for Internet Protocol. 192.0.2.172 (IPv4) or xx.xx.xx.xx.xx.xx.xx.xx (IPv6).

What is a router?

-- A router is a device which connects a network of devices to the internet.

What is an ISP?

-- An ISP is an Internet Service Provider. It is a company that manages special routers which communicate with other ISP routers. ISP networks to ISP networks to get the information to you.

What are packets and how are they used to transfer data?

-- Packets are small segments of data that form the larger message when they are recieved together. They are used to transfer data/messages over the internet in an efficient and timely manner. 

What is a client?

-- A computer that can send and recieve information in a network.

What is a server?

-- A Server is a special computer connected directly to the internet, and provides data/services to clients (computers) on a network.

What is a web page?

-- A web page is a file that is located on a server's hardrive and is displayed to a client when a request is made for that file from a web browser.

What is a web browser?

-- With a web browser, you can view and access content on the World Wide Web. An example of a web browser is Chrome, which needs the search engine Google to first locate web pages / content, and then Chrome can display them / interact with the content.

What is a search engine?

-- This is a website which helps you locate web pages. They are often used in conjuction with a web browser to display web pages. For example, Google is the search engine to find web pages, and Chrome is the web browser that displays the pages that you request.

What is a DNS request?

-- This request is made from your browser to a Domain Name System server to retrieve the IP address of that domain.

Which browser are you currently using?

-- Chrome 127

In your own words, describe the process that takes place when you initiate a search on google.com in terms of what we discussed.

-- From the top, you connect a modem to an ISP to get internet access. You connect a router to the modem to route this internet access to the devices in your home network. Let's say you decide to use your computer which is connected to the internet to find something. You open up the web browser Chrome, and are greeted by the website, Google. From there you search with Google and select a web page. The operating system of the client makes a DNS request to the DNS server for the IP address of this web page. Once this is provided, the web server that is hosting the web page can be located via the IP address, and the browser makes a http GET request on a port of the web server (usually 80). The web server then displays the web page to the client if the request was successful.

#
# Command Line Basics

What is the command line?

-- A shell which allows you to communicate with the computer through text commands.

How do you open the command line on your computer?

-- cntrl + alt + t

How can you navigate to a particular directory?

-- cd [path]

Where will cd on its own navigate you to?

-- your home directory

Where will cd .. navigate you to?

-- one directory up / back

How do you display the name of the directory you are currently in?

-- pwd

How do you display the contents of the directory you are currently in?

-- ls

How do you create a new directory?

-- mkdir [directory name]

How do you create a new file?

-- touch [filename] or nano [filename]

How do you destroy a directory or file?

-- rm [file] in general or rmdir [directory] for an empty directory

How do you rename a directory or file?

-- mv [old name] [new name]
#
# Introduction to Git

What kind of program is Git?

-- Git is a Version Control System (VCS) program.

What are the differences between Git and a text editor in terms of what they save and their record keeping?

-- Git records changes to files over time, while a text editor simply allows you to edit files and overwrite what was previously available.

Does Git work at a local or remote level?

-- Git works at a local level, on your local machine.

Does GitHub work at a local or remote level?

-- GitHub works at a remote level, by hosting a repository of your files and their different version histories.

Why is Git useful for developers?

-- Git is useful for developers because it allows developers to save previous versions of their work whilst tracking changes, and as a result developers can develop with the peace of mind that any mistake won't be truly fatal to their project, since there are backups.

Why are Git and GitHub useful for a team of developers?

-- Git and GitHub make collaborating on a project seamless. Through these programs, developers can work in their own branches, see the work of their collegues on other branches, and keep up to date with the latest version of the repo on the main branch.

#
# Git Basics

How do you create a new repository on GitHub?

-- Click "+" on creating a new repository.

How do you copy a repository onto your local machine from GitHub?

-- git clone

What is the default name of your remote connection?

-- origin

Explain what origin is in git push origin main.

-- "origin" is shorthand for the url of the remote repository where the local repo was cloned from.

Explain what main is in git push origin main.

-- "main" is the name of the main branch of your remote repository.

Explain the two-stage system that Git uses to save files.

-- First you git add the files to staging with the changes that you want already done, and then you git commit those changes on your local machine

How do you check the status of your current repository?

-- git status

How do you add files to the staging area in Git?

-- git add

How do you commit the files in the staging area and add a descriptive message?

-- git commit -m

How do you push your changes to your repository on GitHub?

-- git push

How do you look at the history of your previous commits?

-- git log

#
# Introduction to HTML and CSS

What do HTML and CSS stand for?

-- HTML stands for hypertext markup language. CSS stands for cascading styles sheets.

Between HTML and CSS, which would you use for putting paragraphs of text on a webpage?

-- You would use html for putting paragraphs of text on a webpage.

Between HTML and CSS, which would you use for changing the font and background color of a button?

--You would use CSS for changing the font and background color of a button.

What is the difference between HTML, CSS and JavaScript?

-- HTML is your base. The basic structure of a webpage and text contents of the page are built with it. CSS is used to make HTML elements looker nicer/ more modern. Javascript is used to enhance the iteractivity of the website and user functions. 

#
# Introduction to HTML and CSS

What is an HTML tag?

-- HTML tags are the opening and closings of HTML elements. Tags basically tell the browser what the content inside the tags are.

What are the three parts of an HTML element?

-- An HTML element consists of an opening tag, some form of content, and a closing tag.

#
# HTML Boilerplate

What is the purpose of the doctype declaration?

-- This tells the browser what version of markup language is being used by the file.

What is the HTML element?

-- This is a subsection of an .html file that contains a certain type of content, wrapped in tags (which describe the content).

What is the purpose of the head element?

-- The head element is used to store content that doesn't show up in the webpage itself. For example, the "title" element contains the words written in the tab space, and "meta" is used to store metadata like the UTF type.

What is the purpose of the body element?

-- The body element stores the content that is displayed on the page and shown to the user.

#
# Working With Text

How do you create a paragraph in HTML?

-- You create a paragraph in html using the "p" tag

How do you create a heading in HTML?

-- You can create a heading in HTML using the "h#" tag. # can be 1-6.

How many different levels of headings are there and what is the difference between them?

-- There are six levels of headings, 1 - 6. 1 is the most important and largest in screen, 6 is the opposite.

What element should you use to make text bold and important?

-- Use the "strong" element.

What element should you use to make text italicized to add emphasis to it?

-- Use the "em" element.

What relationship does an element have with any nested elements within it?

-- A parent child relationship where the child elements belong / pertain to the parent elements.

What relationship do two elements have if they are at the same level of nesting?

-- This means they hold an equal level.

How do you create HTML comments?

-- Using <, and exclamation point, and --, and closing using -- with >. You can also start comments using cntrl + /.

#
# Lists

What HTML element is used to create an unordered list?

-- "ul" element

What HTML element is used to create an ordered list?

-- "ol" element

What HTML element is used to create list items within both unordered and ordered lists?

-- "li" element

#
# 
