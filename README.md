# Coder Academy Diploma of IT - T1A1 Workbook - Ethan Cornwill

## Q1: Identify and explain common and important components and concepts of web development markup languages

Markup languages describe how content is structured, laid out, and presented on web pages. They are more forgiving than programming languages are. For instance, an HTML coding mistake won't cause the website to crash the way an error might in a language like Python. 
The most often used markup language, HTML originated in GML and SGML, Standard Generalised Markup Language. These simpler languages cleared the path for HTML and XML. 

Because of its importance in online design, most web developers begin their coding journey by learning a markup language, most often HTML. There is a connection between the word "markup" and the editing process in physical media, where text is "marked up" with typesetting directions. 


https://hackr.io/blog/what-is-markup-language
https://www.semrush.com/blog/markup-language/

---

## Q2: Define the features of the following technologies that are essential in terms of the development of the internet

- Packets
- IP addresses (IPv4 and IPv6)
- Routers and routing
- Domains and DNS

> Explain how each technology has contributed to the development of the internet.

### Packets

The term "packet" is used in the field of networking to refer to a smaller component of a larger message that is being transmitted for the purpose of communication. They are used for the purpose of partitioning the data that is being transferred via computer networks such as the Internet or other networks that are believed to be equivalent. These packets are used for this purpose. Once these packets have been received by the computer, the computer or other device that is handling them will recombine them into a single packet. 

https://www.cloudflare.com/learning/network-layer/what-is-a-packet
https://www.keycdn.com/support/network-packets

### IP Addresses

An IP address is a unique string of numbers for every device on the internet. Originally, we had IPv4, which had 32-bits. Unfortunately, the amount of addresses we could assign was limited by its design as it was designed to use a 32-bit structure. As a result of IPv4 addresses quickly running out, IPv6 was created. This has 128 bits. The creation of IPv6 has significantly boosted the number of addresses that can be created and has also improved routing and security.

An example of an IPv4 address is '192.168.1.1'. This format has four groups with values ranging from 0 to 255 separated with a decimal point. 

In contrast, '2001:0db8:85a3:0000:0000:8a2e:0370:7334' is an example of an IPv6 address. IPv6 addresses are eight groups of four hexadecimal digits, significantly increasing the address space to handle the expanding number of internet-connected devices. The shift from IPv4 to IPv6 is ongoing.

https://www.fortinet.com/resources/cyberglossary/what-is-ip-address
https://whatismyipaddress.com/ip-basics

### Routers and routing

Routers can direct data packets to their intended destinations by taking advantage of the most efficient pathways available. The use of routeing tables, which are used by routers, makes this a viable alternative. Routers are considered technical devices. Routeing can be static or dynamic, depending on the conditions. Something like this can happen from time to time. Routeing is the technology responsible for selecting these paths, and dynamic routeing allows for more efficient data transit over complex networks. 

https://www.cloudflare.com/learning/network-layer/what-is-a-router/
Cisco 2023, What is a Router? - Definition and Uses, Cisco, viewed 28 May 2024, <https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/what-is-a-router.html>.

### Domains and DNS

From domain names like google.com, the Domain Name System (DNS) gives you an IP address. This is needed to find different servers over the internet. When you type in a domain name, the DNS resolver contacts the root nameserver to start the process. For example, if the domain ending is .com, the root points it to the TLD nameserver that matches that extension. A similar process is followed for all other TLD's as well, such as .net, .org, and .com.au. Once that's done, this TLD nameserver points the resolver to the domain's authoritative nameserver, which has the real IP address of the server that hosts the website stored. By using this IP address to connect to the server, your browser can load the page for you. This innovative technology makes it easier to get to websites, which makes the whole online experience perfect.

Cloudflare. (n.d.). What is DNS. Retrieved May 28, 2024, from [https://www.cloudflare.com/learning/dns/what-is-dns/](https://www.cloudflare.com/learning/dns/what-is-dns/)

---

## Q3 Define the features of the following technologies that are essential in terms of the development of the internet

- TCP
- HTTP and HTTPS
- web browsers (requests, rendering and developer tools)

> Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

### TCP

The Transmission Control Protocol, commonly known as TCP, is an essential network standard that facilitates reliable data exchange between various devices within a computer network. It is designed to establish a robust connection between two endpoints, allowing for a seamless two-way data transmission. This bidirectional flow of information is akin to a telephone conversation, where both parties can simultaneously send and receive data. Each data packet transmitted via TCP is acknowledged by the recipient, ensuring the integrity and reliability of the communication. TCP segments, which are the fundamental units of data transmission, are systematically organized to maintain the order and completeness of the data being exchanged. This protocol is integral to the functioning of the internet, underpinning a vast array of network communications and ensuring that digital information is accurately shared across the globe.

https://www.ionos.co.uk/digitalguide/server/know-how/introduction-to-tcp/
https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:transporting-packets/a/transmission-control-protocol--tcp


### HTTP and HTTPS

HTTP, which stands for Hypertext Transfer Protocol, serves as the foundation for web communication. It enables data transfer between clients (such as web browsers) and servers. However, HTTP communication is unencrypted, meaning that data transmitted over HTTP can be intercepted and read by anyone. This lack of security poses risks to user privacy and sensitive information.

In contrast, while HTTP facilitates communication, HTTPS significantly improves security by encrypting data, verifying server authenticity, and maintaining data integrity. So, when you see that padlock icon in your browser’s address bar, you know your connection is secure!

https://hackernoon.com/http-made-easy-understanding-the-web-client-server-communication-yz783vg3
https://www.freecodecamp.org/news/what-is-https-http-vs-https-meaning-and-how-it-works/
https://study-ccna.com/http-https/

### Web Browsers

Web browsers play a crucial role in client-server communication.
Web browsers communicate with web servers using HTTP.
When you click a link, submit a form, or perform a search, the browser sends an HTTP request to the server.
The server processes the request and generates a corresponding response, which includes the requested resources (such as HTML, CSS, JavaScript, images, etc.).
The web browser then renders the response on the screen of the user's device.

Before making the request, the browser performs a DNS lookup to convert the URL to an IP address.
This IP address corresponds to the web server or server pool that hosts the website.
The browser then initiates a TCP connection to the server through its IP address

https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Client-Server_overview
https://dev.to/danielmabadeje/how-web-browsers-and-servers-communicate-54am
https://www.lifewire.com/web-browsers-and-web-servers-communicate-817764

---

## Q4 Describe the features of interpreters and compilers and how they are different

Interpreters read and execute code line by line at runtime. They don’t wait for the entire source code to be converted into machine code before executing it. Each line of code is executed immediately.
Compilers read the entire source code in one go and generate machine code for later execution. The entire source code is bundled and translated into machine-readable executable. Errors are flagged at compile-time during development.
In summary, interpreters execute code directly, while compilers translate code before execution. Interpreters are great for debugging, while compilers offer faster performance and enhanced security

https://thecontentauthority.com/blog/interpreter-vs-compiler
https://www.makeuseof.com/interpreters-compilers-what-how-different/
https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter
https://top10codingbootcamps.com/blog/what-is-the-difference-between-compiler-and-interpreter

---

## Q5 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each

### Python

#### Benefits
- Large Community and Resources
    - Python boasts a vast and supportive community, making it easy to find help, libraries, and frameworks.
- Versatility
    - Python is used for data analysis, machine learning, web development, scientific computing, and more.
- Readability
    - Its clean syntax and indentation-based structure enhance code readability.

#### Drawbacks

- Slower Execution
    - Being an interpreted language, Python can be slower than compiled languages like C++ or Java, especially for CPU-intensive tasks1.
- Global Interpreter Lock (GIL)
    - GIL restricts true parallel execution in multi-threaded Python programs.

### JavaScript

#### Benefits

- Ubiquity
    - JavaScript is everywhere in web development. It’s essential for creating interactive web pages and runs in browsers.
- Front-End and Back-End
    - JavaScript can be used for both front-end (user-facing) and back-end (server-side) development.
- Frameworks and Libraries
    - Rich ecosystem with popular frameworks like React, Angular, and Vue.js.

#### Drawbacks

- Asynchronous Complexity
    - Managing asynchronous code can be challenging due to callbacks, promises, and async/await.
- Dynamic Typing
    - JavaScript’s dynamic typing can lead to runtime errors if not handled carefully.

https://www.freecodecamp.org/news/python-vs-javascript-what-are-the-key-differences-between-the-two-popular-programming-languages/
https://flexiple.com/compare/python-vs-javascript
---

## Q6 A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself

Hi Alex,

I appreciate you getting in touch with what you want for the website of the Super Awesome Museum. Finding about your varied collection and the museum's dedication to cultural enrichment excites me.

I can definitely assist you in designing a website that not only highlights your exhibitions but also gives guests a simple means of exploring the museum and its resources. Interactive maps for destinations, thorough pages for every exhibit, and a contact form for questions. We could also utilise an event calendar to let guests know about upcoming shows and activities.

Technical-wise, i will make sure the website is accessible on all devices using responsive design ideas, and we will apply SEO best practices to raise your search engine result visibility. We could look thorough on content management systems like WordPress, which would let your staff quickly update the website without much technical experience.

Suggest a reasonable time for when you would be most likely to talk further about this project. Helping the Super Awesome Museum become more online active excites me.

Warm regards,

Ethan Cornwill
Web Developer


---

## Q7 Think back to a scenario or situation in your own software development projects or work

> Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.

Reflecting on the development of the PokerBo app, one scenario that stands out is the initial planning phase. 
In retrospect, a more thorough planning process would have been more effective. This would involve pre-planning the features to include in the app, such as the betting system, and the user interface.
If given another opportunity, I would prioritise setting up a kanban board and planning out the development of the app before beginning development. This approach ensures that the app doesn't experience scope-bloat, and the features are well planned out before development, allowing me to create the app easier.

Additionally, I would incorporate user feedback into the development process. This would help me improve the app's user experience. 


---

## Q8 A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops

Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.

1. Australian Computer Society (ACS) Events:
    - Look into Melbourne's ACS events. IT specialists, industry professionals, and thought leaders meet for these professional development sessions and networking events. Attend conferences, workshops, and seminars to establish connections with individuals who share your interests.

2. Local Meetup Groups:
    - Participate in professional networking groups based in Melbourne on platforms such as Meetup. Looking for meetups that are tech-focused and relevant to my pursuits, including programming languages, web development, or home automation. Attend events and participate in discussions to establish connections.

3. LinkedIn:
    - Enhance my LinkedIn profile and establish connections with IT professionals in my vicinity. Reach out to potential contacts, participate in groups, and share pertinent content to engage. Join LinkedIn groups that are specific to Melbourne.

4. Tech Co-working Spaces:
    - EInvestigate co-working spaces that are designed for technology enthusiasts. Workshops, networking events, and lectures are frequently conducted in these locations. It is an excellent method for interacting with other entrepreneurs and developers.

5. Volunteer Opportunities:
    - Participate in community events, hackathons, or tech conferences as a volunteer. I am able to expand my network, interact with industry experts, and acquire experience through volunteering.
---

## Q9 Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects

ChatGPT and other language-learning model technologies have completely changed the way technical and literary works are approached. When it comes to report writing, these models can help with data analysis, complicated information  summary, and even section drafting, which can make things more efficient and accurate. They offer conversational interfaces for debugging, create code according to standards, as well as contributing to code documentation for software projects. By providing explanations in a user-friendly, natural-language format, these models can also help students understand programming languages and technical topics. In general, language-learning technologies are great resources for making many technical fields more accessible, efficient, and of higher quality.


---

## Q10 Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects

When language-learning programmes like ChatGPT are used in technical and written works, they raise a lot of legal and moral questions. When these technologies are used, it can be hard for lawyers to understand intellectual property rights, especially when AI-made content is added to reports or software. Who owns the rights to writing that AI writes? That person, the client, or the AI itself? Ethics-wise, AI results might be biased, which could make already existing issues in society worse if the data used for training isn't right.
Relying on AI to do things like write legal papers or code a piece of software could make it hard to keep it accountable. For example,  a paper written by an AI might be hard to defend in court because it might be hard to understand what the AI was thinking when it wrote it. Also, automating things that people have always done could change how jobs are made and make people worry about their future jobs. It is also important to make sure that AI works in a clear and private way and that people agree before their personal data is used to build language models. Overall, using AI to help people learn languages needs to be done in a way that is both new and follows the law and morals.

---

## Q11

Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

### Soft skills

### Hard skills

---

## Q12 Explain multiple roles or job positions that would be found in a medium-sized software development company
