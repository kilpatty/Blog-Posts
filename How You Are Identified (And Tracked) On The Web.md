I see a lot of misconceptions when it comes to understanding how the "evil overlords" of the internet track us.

As a developer myself, this is a brief overview of some of the most common methods of identifying and tracking unique users.


#### IP Address

Everything connected to the internet needs an IP address. Your laptop, Xbox, Smart TV - All have unique IP addresses. Despite this, very few devices in your day to day life have static IP addresses. That is, an IP that does not change.

When you "rent" internet from an ISP (Internet Service Provider) such as Comcast or Google Fiber, you are most likely just renting the IP addresses. That means that your IP is dynamic - it could change.

Therefore while IP addresses are a good way to track devices that don't often change wifi networks, in the overall scope of things IP Addresses alone aren't very effective at identifying unique users.

There is no real way to completely hide your IP from those who need to attain it (authorities). That being said, most large websites do not have the tools to do this, therefore there are some small things you can do to hide your IP if you are so inclined.

1. Using a service such as [Tor](https://www.torproject.org/).

2. VPN - Using a VPN can mask geolocation information, but by using the same IP (the VPN's IP) every time you access a site, you won't prevent them from identifying you by that IP address.

3. Proxy

If you want to investigate these methods of concealing your IP address further I suggest reading this [How to Geek article](http://www.howtogeek.com/247190/whats-the-difference-between-a-vpn-and-a-proxy/).


#### Fingerprint

Your Fingerprint is also known as your browser fingerprint online. It is a combination of many configurations and settings on your specific browser that attempts to identify your browser as unique.

What exactly does this mean? Suppose we took your browser version: Chrome 55, Operating System version MacOS 12.2.2, fonts in browser, etc... and hashed them all together. There is about an 84% chance that this will create an entirely unique fingerprint for your browser, even more (94%) if you use Flash or Java.[^1] If you use both Firefox and Chrome that is 2 unique fingerprints. Mobile browsers will also have unique fingerprints.

While fingerprinting can be useful by itself, it becomes much more powerful when combined with other factors. A similar IP address, and the same browser fingerprint? A website can make a confident guess that that session is from a recognized device of yours.

There isn't much that can be done to prevent fingerprinting of your browser. Some things can be disabled which decrease the percentage of having a unique fingerprint, but for the most part it is hard to combat it.

If you want to find out if your browser is unique check out [AmIUnique.org](https://amiunique.org/).

#### Cookies

Cookies are pieces of information that are stored in your browser. Websites will create a cookie for you that can contain certain information to identify you when you return to their website. Cookies are persistent, so unless you specifically remove them they will most likely remain throughout a browser closing.

Using private browsing such as Chrome Incognito mode can prevent cookies from being stored on your sessions. You can also delete cookies from your browser.

For more information on deleting or preventing the usage of cookies I recommend [SaferVPN's article](https://www.safervpn.com/blog/tracking-cookies/).


#### Logins

Everytime you log into a service or grant access to a service, you are allowing them to track you more effectively. Just this year Google joined Facebook in [tracking you by name](http://www.techworm.net/2016/10/google-now-officially-joins-facebook-tracking-name.html) across different websites.

Despite how easily "sign up with Facebook/Twitter/Google" have made signing up for new services, this comes with a cost. Everytime you do this you grant both that service access to a certain amount of information about you as well as Facebook/Twitter/Google more tracking information about you.

If you truly care about your privacy, being aware of what you sign up for and with what login should be of the highest priority.


##Should I protect myself from website tracking me at all?

That is an interesting question. For a lot of people this is a matter of personal privacy. They don't want a website knowing who they are or their information and selling it to others. While this is definitely an important matter to note, it is also interesting to see the other side of user tracking.

I try to recognize users coming back to my application so that I can make the application easier for them to use. If I know with a 99.99% confidence ratio that you are who I think you are, then I'm not going to waste your time with extra security measures such as one time passwords. I'm just going to let you right in making the experience much more enjoyable for you.

User tracking isn't all that bad. It can be an important tool to implement when you need to improve your UX without forgoing certain security measures.

Further Reading:

* [How Private Browsing Works](http://www.howtogeek.com/117776/htg-explains-how-private-browsing-works-and-why-it-doesnt-offer-complete-privacy/)

---


[^1]: https://panopticlick.eff.org/static/browser-uniqueness.pdf

 
