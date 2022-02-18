## Blog Post 2

### February 10, 2022

As mentioned in the previous blog post, the field of web development is very diverse and requires collaboration between people of all different specialties.  There are UX designers that create the stylized look of the website, web developers that bring it to life with code, information architects that map out a wireflow of all the different web pages, and user testers that test the product against potential users.

There are also the system architects, who oversee the organizational structure of their projects.  There are two main structure types:  monoliths and microservices.  However, there is a large spectrum between these two, and most projects fall somewhere in the middle.

The names of these structures are fairly self-explanatory.  In a monolith, the entire website is built by the same team and contained in one massive, overarching system.  It is designed to be a single, self-sufficient program, all the components of which are interconnected.

In microservices, the opposite is true.  Instead of one larger system, the project is split up into many smaller ones, each built by a separate team of developers.  All of these programs are still connected, albeit much more loosely, and come together to form the final product.

![A monolith vs microservices](img/monolithVsMicroservices.png)

There are pros and cons to both of these approaches.

**Monolith:**

| Pros | Cons |
| --- | --- |
| Easier to build in the beginning | More vulnerable to breaking |
| Whole thing can be changed at once | Difficult to change in later stages |

**Microservices"**

| Pros | Cons |
| --- | --- |
| Changes limited to their area | Takes a while to get started |
| Easier to modify in later stages | Requires more coordination between groups |

A monolith is easier to build in the short term because it is easier to coordinate a single cohesive team than many individual ones.  This allows communication to be streamlined, and different parts of the project are more consistent with each other.

However, in the long term, monoliths are not nearly as convenient.  Once set, they are more difficult to change, as a change to one aspect of it affects the entire structure.  If something is changed in a certain place, it must also be changed everywhere else to maintain consistency.  This makes it more vulnerable to breaking.

One of the reasons that microservices are so popular is that they solve many of these problems posed by monoliths.  The fact that all their systems are developed independently gives them greater flexibility to be changed in later stages.  A change in one area is contained there and will not necessarily affect the entire program.

On the other hand, though, microservices are significantly harder to get off the ground.  They require a great deal of coordination between multiple teams, each with their own specialties and goals.  Once built, they are very useful, but initially, they can be very hard to get off the ground.

The takeaway from all this is that monoliths and microservices are both useful in different circumstances.  Monoliths work best when it is a smaller project, one that does not need to be broken up into separate programs.  At a certain size, microservices are more trouble than they’re worth and might as well be combined.

Microservices are ideal with larger-scale systems that would be too inconvenient to combine into the same program.  Once they reach a certain size, the hassle of needing to modify everything whenever a change is implemented negates the benefits of everything being interconnected.  There is no one-size-fits-all, though, and most projects fall somewhere in the middle of these two extremes.
