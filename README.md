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
# CLI Basics

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

