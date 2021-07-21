## 1: Setting up my Website

### Conception
At the start of the summer I decided to build myself a website. It's been apparent to me that I needed a website for a few months now, but the infrastructure that I needed to build the site has only recently become available. There are three types of professional development in the computer science industry; networking, skills and accomplishments, and traditional professionalism.On my website, My LinkedIn represents my networking profile, my Github displays my general skills and accomplishments, and my Resume provides a traditional way to show my accomplishments. My hope is that this website will grow alongside my career and give me a way to reflect on my accomplishments thus far.

### Inspiration
[marco.org][1] and [daringfireball.net][2] both served as inspiration when creating my website. Both of these websites are well designed and give good insight in their respective developers. The websites are both [static][3], meaning that they are organized as a system of HTML and CSS files. These websites include little to no JavaScript and aren't web apps. These websites run in every browser and are extremely light on system resources. I wanted to emulate these websites' minimalistic approach to web design in my own website, which led to a number of benefits. My entire website is hosted and visible on [my GitHub repo][4] and as changes are made to my website they are visible in my GitHub. Developers in the future can use the website as a reference, or even download the webpage to be viewed offline. All of these features made a static in the style of the two mentioned above the most obvious choice when designing my website.

### Hosting
I settled on [Cloudflare Pages][5] as my web hosting provider. Cloudflare provides a few features that place it above the competition with the most notable being built in security. Cloudflare pages comes with the ability to dictate connection types (SSL/TLS), the ability to mitigate DDOS attacks, and generally survey web analytics. This allows me to monitor my website for attacks and ensure a safe connection for people who view my site. Cloudflare also provides the ability to register domain names and deploy changes to my website from my GitHub repository automatically. This flexibility abstracts away many elements of the web development process while still providing security and a simple interface for deploying my site.

### Conclusion
I am very happy with the tools I chose to implement my website. The simple static nature of my website means that my website is accessible, loads quickly, and is easily and widely available. The Hosting provided by Cloudflare ensures entry level security and abstracts away the finicky details of server maintenance and website deployment. The inclusion of a [GitHub Repository][4] makes it easier to track changes in my website and serves as a resource for myself and future developers.

[1]: https://marco.org "Marco Arment's Website"
[2]: https://daringfireball.net "Dave Gruber's Website"
[3]: https://en.wikipedia.org/wiki/Static_web_page "Static webpage Wikipedia Article"
[4]: https://github.com/Trevor-Opiyo/Trevor-Opiyo.github.io "Trevor Opiyo's Website Repository on GitHub"
[5]: https://pages.cloudflare.com "Cloudflare Pages Website"