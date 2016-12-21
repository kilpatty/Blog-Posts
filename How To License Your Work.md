If you follow along with the news for the programming world, you've most likely seen the recent discussions surrounding licensing at several large companies. Facebook came [under fire](http://react-etc.net/entry/your-license-to-use-react-js-can-be-revoked-if-you-compete-with-facebook) for it's license on React - forcing them to release a FAQ on the terms of their license, and Automattic's founder Matt Mullenweg [accused Wix](https://ma.tt/2016/10/wix-and-the-gpl/) of violating Wordpress's GPL Licensing in Wix's new mobile application.

Licensing seems to be an enigma for the developers that I talk with on a day to day basis. Most of them simply slap a MIT license on anything that they do and call it a day. While this isn't necessarily bad, it can be helpful to understand exactly the rights that you are granting with each license, and all of your options for doing so.

Licensing isn't just for programming. It's an important piece in all of content creation whether it's hardware, software, art, writing, or anything else that you create.

This article isn't going to graduate you from law school with respect to licensing. I'm going to give you what I hope is a very broad knowledge on licensing, as well as the resources to dive deeper into specific categories.


##Open Source Licenses

Everyone has heard of Open Source Software, but few can actually give you an exact definition of what this means. Open Source essentially means that it is completely open for anyone to view, modify, and distribute the product. OpenSource.org has a very [digestible list of criteria](https://opensource.org/osd) that must be met to be considered Open Source.

For a license to be fully Open Source, it has to be approved by the OSI (Open Source Initiative). The full list of Open Source Licenses can be found on [OpenSource.org](https://opensource.org/licenses). The following are some of the more popular licenses along with a brief definition.

###[MIT LICENSE](https://opensource.org/licenses/MIT)

The MIT license allows essentially all uses of the product, as long as the copyright and licensing information are continued along with the use. It is very to the point, and a great option for a lot of open source software.

###[APACHE 2.0](https://www.apache.org/licenses/LICENSE-2.0)

The Apache license also allows for essentially any use of the product, but with a few more restrictions. Any changes made to the product must be stated. The license explicitly states that it does not grant any trademark rights, while additionally granting the use of patents, whereas the MIT license does not explicitly grant that use of patents.

If you are curious about the patent provision in the Apache 2.0 license, I suggest reading [this](http://oss-watch.ac.uk/resources/apache2) great overview.

###[BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)
The BSD 2-Clause License is essentially identical to the MIT License. The BSD 3-Clause License combines the 2-Clause License with the "no-endorsement" clause, which states that the licensor can't be used to endorse any product that includes this code without written permission.

### [GNU GPLv3/LGPLv3](https://www.gnu.org/licenses/gpl-3.0.html)

The GPL license is famous for being a "copyleft" license. Copyleft means that any project using something licensed with a copyleft license, must also be licensed with that license. What this means is that if you use GPL licensed code in your project, your project must also be licensed as GPL.

This copyleft licensing is what put [Wix in deep water](http://arstechnica.com/information-technology/2016/11/wordpress-and-wix-trade-shots-over-alleged-theft-of-open-source-code/) because they used Wordpress's GPL code in their mobile app without licensing their application as GPL.

LGPL is a similar but less strict license that allows for a project to license the portion of their code that contains other LGPL code as LGPL, while retaining a different license on the rest of the project.

###[The Unlicense](http://unlicense.org/)

The Unlicense is as free as the MIT License without the clause of including the copyright information. It states that the product is "public domain", and thus can be freely used in any manner with no attribution whatsoever.

If you are looking for a license for a project, Github created a website called [Choose a License](http://choosealicense.com/) that helps you find the perfect license for a multitude of different types of  projects.


##Creative Commons Licenses

Creative Commons Licenses are commonly used to help license things that are not software such as content, media, and art.

Medium allows you to easily [apply CC licenses to your content](https://medium.com/@Medium/licensing-your-work-on-medium-517fa7096e62#.h1p7h6h64) when you publish it.


### [CC BY (Attribution)](https://creativecommons.org/licenses/by/4.0/)

The CC Attribution license is the MIT license of the content world. It essentially allows for full modification, and distrubtion of your content as long as you are credited for the original.

### [CC BY-SA (Attribution-ShareAlike)](https://creativecommons.org/licenses/by-sa/4.0/)

The CC Attribution-ShareAlike license is most similar to the GPL license. It is a copyleft license, and thus requires all new creations to be licensed under the same terms.

### [CC BY-ND (Attribution-NoDerivs)](https://creativecommons.org/licenses/by-nd/4.0/)

The CC Attribution-NoDerivs license allows for full distrubtion of your content as long as their are no modifications, and credit is given to the content creator.

The [Creative Commons Website](https://creativecommons.org/licenses/) has a full list of their available licenses.

##Licensing for Profit

I will only touch on this briefly, as I personally would leave this kind of licensing to lawyers. It is important to note that licensing is not only for free to use code, or media - licensing is important when it comes to selling code or your content.

I will refer you to the following resources on licensing your content for monetization:

* [Graphic Artists Guild - License It](https://graphicartistsguild.org/tools_resources/license-it)

* [Creative Bloq - License Your Designs](http://www.creativebloq.com/design/license-your-designs-9134535)

* [GNU - Selling](https://www.gnu.org/philosophy/selling.en.html)


##Multiple Licenses

Multiple licenses can also be used to license certain products. On my [personal website](https://github.com/Skilgarriff/SeanKilgarriff.com/blob/master/LICENSE.md), I use two licenses - one to license the code, and one to license the content of my blog.

Github's [Choose A License website](https://github.com/github/choosealicense.com#license) also employs this same strategy.


##No License

When no license is included in a project, it assumes that no rights are granted. Therefore on Github, if no license is included in the project, people can view and fork your repository, but that are legally not allowed to use the code or reproduce it in anyway.  - rewrite this.

On Medium, when no license is explicitly defined, your work defaults to an [All Rights Reserved License](https://medium.com/policy/medium-terms-of-service-9db0094a1e0f#.qi1i1pc1m).


If you haven't yet, I highly recommend licensing your work whether it's on Github, Medium, or your personal blog. It's a great way to ensure controlled sharing of your work!


Further Reading:

*
https://opensource.com/law/14/7/lawsuit-threatens-break-new-ground-gpl-and-software-licensing-issues


[Submit a correction](https://github.com/Skilgarriff/Blog-Posts).
