# Introduction and Background

During the spring semester of 2018, the University of Idaho redesigned their website and updated their brand, revising the official logos and color schemes (University of Idaho 2018). Like many libraries, the University of Idaho Library independently hosts and maintains its own website, so this university-wide rebranding meant the library website would need a "refresh" as well, to avoid being out of sync with the new look and feel. One might think this would be as easy as swapping out the web banner logo and updating the accent colors (Figures 1 and 2).

![university of idaho logo with metallic gold lettering](DtNFdB.jpg "Figure 1")

Figure 1. The old University of Idaho Library Logo, from <https://web.archive.org/web/20180224063150/https://www.lib.uidaho.edu/>

![university of idaho logo with large I](JGJxZF.jpg "Figure 2")

Figure 2. The new University of Idaho Library Logo, 1/30/2020.

However, as University of Idaho librarians soon discovered, this cosmetic update was not so simple. Attempts at a quick patch for the new branding were unsatisfying, prompting a long, considered look at the evolving needs of the library's users and the library's overall approach to producing the website. In June 2018, the Library's web team decided that the library needed to completely overhaul its website and development process, and that process needed to be completed by the start of the fall semester in early August. In effect, the university's brand refresh triggered a cascade of change in the technical stack, workflows, and culture behind the library's website---all in a few short months.

::: box :::

Markdown content within the box! Such as:

**A List:**

- list item
- list item
- list item

:::

An academic library's website plays a crucial role in how it is perceived and utilized by patrons and visitors. Rebuilding that website and establishing a new development style can be an exceptionally difficult process: librarians face an increasingly overwhelming array of choices for deciding on a web platform that fits their context. Investing in an effective platform almost always involves exchanging a certain amount of control over a site's structure and content in order to gain ease of use or convenience. In part, this is a result of libraries lacking dedicated resources and staffing to create and maintain a website full-time. Historically, many libraries have built websites using content management systems (CMS) that allow for participation from staff without formal web development training, yet are expensive, difficult to customize, and prone to security issues. On the other hand, libraries that forgo a CMS often find that collaborative participation in web design and deployment is restricted only to those with the requisite technical skills.

Not wanting to submit to the lack of control that a CMS requires, yet still desiring an effective means of collaboration, librarians at the University of Idaho Library have developed a modern static web approach for building the library website that offers a viable middle-way. Using the static site generator Jekyll to simplify modular development and the code hosting platform GitHub to facilitate collaboration, librarians produced a complete website composed of static assets without the server-side processing and databases used by dynamic web applications such as CMS. This provided a low-cost, highly customizable, and secure solution with minimal infrastructure requirements.

This case study explores the theoretical reasoning behind implementing a static library website and the practical steps taken to establish an agile yet sustainable development model. Ultimately, the site's creators have found that the most important result of this process is not technical, but social and organizational. The ideals and methods of the static web approach have contributed to an inclusive web development environment in which increased participation empowers librarians and staff to learn and work with basic web development languages and concepts, in turn producing a more robust and uniquely customizable library website.
