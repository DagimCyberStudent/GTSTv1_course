                       Web Hacking
                What is Web Application?
           ● A web application is a program or software that runs on a web browser to perform specific
            tasks.
           ● These web applications are made with programming languages like
                    -> HTML,CSS,JS(node,react,angular),Python(Django,Flask)
            ● WebSites Consists 2 parts.
                ○ Front End / Client side /
         ■ Front End is the Front page/ the page which we access, the graphical part.
          ■ There are specific Programming languages and Frameworks to build front end of a
            website.
                 ● Example: HTML,CSS,JS(react)
           ■ A person who develop Front end is called “Front End Developer”
              ○ Back End / Server Side /
         ■ Back End is another side of a web which users don't have interaction with it, but
           their requests will be sent to the server and used to fetch the data from server
           and hands to the front page/front end/ of the websites.
         ■ Also here there are Specific Programming languages
                ● Example: JS(node.js),Python(Django,Flask),PHP,SQL
         ■ A person who develop Back end is called “Back End Developer”
                ● A person who develop Both Front and Back end is called “Full Stack Developer”
             What is web hacking
      ● Web hacking refers to exploitation of applications via HTTP which can be
        done by manipulating the application via its graphical web interface.
      ● It is The another Big Scope of Cyber Security
              How do websites work?
        ● When you access a website or click a link, it will send a HTTP request to the server and get the copy of the website files to the client this is called HTTP Response.
             URL and URI
      ● URI identifies: a resource and differentiates it from others by using a name,location, or both.
      ● URL identifies: the web address or location of a unique resource.
      ● URI contains components like a scheme, authority, path, and query.
      ● URL has similar components to a URI, but its authority consists of a domainname and port.
      ● A URI aims to identify a resource and differentiate it from other resources by using the name of the resource or location of the resource.
      ● A URL aims to find the location or address of a resource on the web.
              ○ An example of a URI can be ISBN 0-486-35557-4.
              ○ An example of an URL is https://www.javatpoint.com.
                 Parts of URL
          A URL consists of five parts:
        1. Scheme: tells web servers which protocol to use when it accesses a page on your website.
        2. Subdomain:
                   a. If your website is like a house, your subdomains are like specific rooms in that house.
                   b. A subdomain in a URL indicates which particular page of your website the web browser should serve up.
                   c. For instance, subdomains like “blog” or “offers” will provide your website’s blog page or offers page.
                   d. Subdomains also bucket your website into its main content categories and shows Google and your visitors that there's more information on your site than just a homepage. ( meet, docs, google.com )
        3. Top-level domain: specifies what type of entity your organization registers as on the internet.
                 a. Generic Top level domain(gTLD): .gov .org .net
                 b. Country code Top-level domain(ccTLD): .et .ru
        4. Second-level domain: is the name of your website.
        5. Subdirectory: also known as a subfolder,helps people understand which particular section of a webpage they’re on. 
              DNS
     ● The Domain Name System (DNS) is the phonebook of the Internet.
     ● When users type domain names such as ‘google.com’ or ‘nytimes.com’ into web browsers DNS  is      responsible for finding the correct IP address for those sites.
     ● Browsers then use those addresses to communicate with origin servers or CDN edge servers to access website information.
     ● This all happens thanks to DNS servers: machines dedicated to answering DNS queries.
     ● The DNS request the goes out from our computer is called “DNS query”.
     ● there are four servers that work together to deliver an IP address to the client: recursiveresolvers, root nameservers, TLD nameservers, and authoritative nameservers.
                    DNS Records
        ● DNS records (aka zone files) are instructions that live in authoritative DNS servers and provide information about a domain including what IP address is associated with that domain and how to handle requests for that domain.
        ● These records consist of a series of text files written in what is known as DNS syntax.
        ● To Access DNS Record on linux we can use tools like
        -> NSLOOKUP       -> Dig      -> Host
                     Types of DNS records
      -> There are Many DNS record Types but lets see some
           A Record ( Address )
       ● This is a Record on the server that holds IPv4 Address.
           AAAA Record (Quad Address)
         - This holds the IPv6 Of the Domain
            MX Record ( Mail Exchange )
          ● Directs mail to an email server.
            NS Record ( Name Server )
          ● Returns the DNS servers (nameservers) of the domain. Server Where all the DNS recordsare stored!
            And more…
          ● There are more Records like
                  ○ TXT
                  ○ CNAME
                  ○ SOA 
                  ○ SRV
                  ○ PTR
          ● If you wanna Have Advanced knowledge on this Try to learn about “Zone Transfer”HTTP request and response
          ● As the name suggests HTTP requests are a request which the browser send sto the server
          ● HTTP responses are a response from the server to the browser.
        ● The requests and Response are sent and received with a Header.
                HTTP Headers
         ● The HTTP headers are used to pass information between the clients and the serverthrough the request and response header.
         ● All the headers are case-insensitive, headers fields are separated by colon, key-value pairs in clear-text string format.
         ● The end of the header section denoted by an empty field header(New line).
                    Types of Headers
            ● General Header: This type of headers applied on Request and Response headers both but without affecting the database body.
            ● Request Header: This type of headers contains information about the fetchedrequest by the client.
            ● Response Header: This type of headers contains the location of the source thathas been requested by the client.
            ● Entity Header: This type of headers contains the information about the body ofthe resources like Content-length.
                   Request Headers
             ● This is A header sent to the server.
             ● In Request Header There are different kind of headers
                        ○ Example: GET, Host, Cookie,...
                   cont…
             The 1st line Contains
                  ● Request Method
                  ● Path: The path where the file/folder is located
                  ● Protocol Type: which HTTP protocol ( HTTP 1 , HTTP/1.1 , HTTP/2
             The 2nd line
                 ● Host: the website link
             The 3rd line
                ● Cookie: used to check a user
              The 4th line
                 ● User-Agent: used to place the browser information
               Response Header
            ● This is response from The server to the browser
              ● 1st line
                    ○ HTTP: Tells the server Protocol
                    ○ Status Code
              ● 2nd line
                    ○ Date: Date of the response sent
              ● 3rd line
                    ○ Content-Type: What type of content the server sent Encode type
              ● 4th line
                    ○ Content-length: The number of the alphanumeric and spaces
              ● 5th line
                    ○ Server: type of the webserver
              ● 6th line
                    ○ This line is empty used to show that the headers ending. And begining of the body
              ● 7th…. Line
                    ○ The html content
                    HTTP request methods
          ● The method designates the type of request being made to the web server.
          ● The most common types of request methods are GET and POST but there are many others, including HEAD, PUT, DELETE, CONNECT, and OPTIONS.
          ● GET and POST are widely supported while support for other methods is sometimes limited but expanding
                    HTTP Status Code
            ● The Status-Code element in a server response
            ● is a 3-digit integer where the first digit of the Status-Code defines the class of response and the last two digits do not have any categorization role.
            ● There are 5 values for the first digit:
                       ○ 1xx: Informational
            ■ It means the request has been received and the process is continuing.
                       ○ 2xx: Success
            ■ It means the action was successfully received, understood, and accepted.
                       ○ 3xx: Redirection
            ■ It means further action must be taken in order to complete the request.
                       ○ 4xx: Client Error
            ■ It means the request contains incorrect syntax or cannot be fulfilled.
                       ○ 5xx: Server Error
            ■ It means the server failed to fulfill an apparently valid request.
         Some common codes
       ● 200 = request is Successful( OK )
       ● 301 = The requested page has moved to a new url . ( Moved Permanently )
       ● 302 = The requested page has moved temporarily to a new url .( Found ) => when there is redirection
       ● 400 = The server did not understand the request. (Bad Request)
       ● 401 = The requested page needs a username and a password. (Unauthorized)
       ● 403 = Access is forbidden to the requested page.(Forbidden)
       ● 404 = The server can not find the requested page.(Not Found)
       ● 405 = The method specified in the request is not allowed.(Method Not Allowed)
       ● 500 = The request was not completed. The server met an unexpected condition.(Internal Server Error)
                Where do you see the headers?
         The headers are shown on some methods.
         1. Developers tool(on browser)
         2. Curl
         3. Burp suite
        Curl on linux
      ● cURL, which stands for client URL, is a command line tool that developers use to transfer data to and from a server.
      ● At the most fundamental, cURL lets you talk to a server by specifying the location (in the form of a URL) and the data you want to send.
      ● cURL supports several different protocols, including HTTP and HTTPS, and runs on almost every platform.
      ● This makes cURL ideal for testing communication from almost any device (as long as it has a command line and network connectivity) from a local server to most edge devices. 
                Burp suite
         ● Burp or Burp Suite is a set of tools used for penetration testing of web applications.
         ● It is developed by the company named Portswigger, which is also the alias of its founder Dafydd Stuttard.
         ● BurpSuite aims to be an all in one set of tools and its capabilities can be enhanced by installing add-ons that are called BApps.
         ● Burp Suite is an integrated platform and graphical tool for performing security testing of web applications
         ● it supports the entire testing process, from initial mapping and analysis of an application's attack surface, through to finding and exploiting security vulnerabilities.
         ● It have a lot of tools all together.
         ● Simply Help Hackers To Act like A Proxy, it will intercept A request,
                 ○ Used to change it or just watch it
               Starting Burp
         ● There are many tabs as you see on the above.
           ○ Target: to add targets inscope & see progress
           ○ Proxy: to setup proxy IP’s also to intercept and watch requests and responses
           ○ Intruder: to Do bruteforce attacks
           ○ Repeater: To do manual checks
           ○ Comparer: to compare 2 requests/reponses
        ● When you Try to open burp next time goto the folder and execute this command
                   OWASP Top 10
       ● OWASP Stands for Open Web Application Security Project.
       ● The OWASP Top 10 is a standard awareness document for developers and web application security.
       ● It represents about the most critical security risks to web applications.
       ● Globally recognized by developers as the first step towards more secure coding.
       ● This Project Releases Top 10 risky vulns every 4 years.
       ● Detail: https://owasp.org/Top10/
       ● OWASP also releases API vulnerabilities
            BruteForce
        ● It is included in Broken Authentication/Access Control Bug
        ● This is a kind of attack that is usually done to a login pages. 
        ● It uses Wordlist and try to check a lot of words in the place of the username and password.
        ● It is a guessing game but the guess is done with computer.
            Foothold
            -> There are some tools, used to Crack Passwords of Files, Hashes
             - Hashcat
             - John The Ripper
            XSS
      ● It is included in Injection Bug
      ● XSS/ Cross site scripting/ is a vulnerability that leads to a lot of huge attacks.
      ● This Bug is exploited. As the following
               ○ If there is a search place and the search place expects a text to search and displays below.
               ○ But if we add some html/JS codes on that place, this means it will add the code to the innerHTML
               ○ SO our code will be executed!
             Cross-Site Scripting
      -> allows attackers to inject malicious scripts into web pages viewed by other users. SO???
      -> They can Use this and Hook your browser with tool called “BeefXSS”
             REMEMBER
        -> All the Injection Attacks are done on some Parameter.
                 SQL injection
         ● It is included in Injection Bug
         ● It is same with xss, but here we will add a sql code to the search place.
         ● SQL is a query language used in Back end to retrieve data from database.
         ● Most of the time used to bypass login pages.
                 SQL Injection
          -> Attackers Use this Vuln to manipulate or gain unauthorized access to a database.
             Rate limit
          ● This is a limiting problem.
          ● Think like if the developers did made a limit to some task.
          ● Example:
                    ○ If there is website , that send an OTP/verification code
                    ○ And if it doesn't limit to some code sends only.
                    ○ I can make the site to send 100000 OTPs to ma phone this means
                    ○ We will make the site to lose a lot of money
                Access Control
          ● This is a problem occurred on how a websites control an access of a user.
          ● If there is a problem on the access control.
          ● Then think that normal user can get access of admins or root user.
          ● This is Good Bug to find because u dont have that much automation tools.
                     IDOR
            ● IDOR/ Insecure direct object references /: is a bug included in Access Control.
            ● This is a bug that happens when you have an id number 1
            ● And is abebe is id 1 then if i changed that number to 0 and got another users information Business Logic
            ● This Bug is a logic Flow.
            ● It occurs by the way how the programmer thinks and hackers thinking.
            ● Think like if You have bank website and it have a purpose of send money.
            ● Then if i can change add to negative numbers
            ● And if the site responded by giving me more money and minimizing the amount of the user i planned to send then this is business logic
            ● Also this is a Good Bug to learn.