### *On Microservices*

  Microservice architecture (MSA) is a big presence in the tech industry. Not that they are necessarily used by everyone, 
but in that they are used heavily by some big players such as Netflix and Amazon. They appear to be here to stay. In 
March 2019 Tech Analysts Anne Thomas and Aashish Gupta wrote a paper, "Innovation Insight for Microservices", discussing 
some of the trade-offs of microservices. In this blog I will give a brief summary of the article.

  First of all, what is a microservice? According to the article, “A microservice is a tightly scoped, strongly 
encapsulated, loosely coupled, independently deployable and independently scalable application component.” In summary, 
it meets three core objectives of agility, flexibility, and scalability. It can be contrasted to a monolithic 
application, where there is a rigid, single structure where all the components are co-dependent.

  Next, we will discuss some advantages. Microservices allow for faster deployment, and being able to be quick with 
software updates or new features is obviously of great use to organizations. There is reduced risk because a bug will 
only affect a single service and not span your entire range of services. Because different components are only connected 
to a limited degree, a range of different tech stacks can be made to work together. Lastly, there is the benefit of 
greater degrees of resilience.

  However, there are some risks involved with microservices besides just the additional cost of switching from macroservices.
One of these is that while microservices can simplify some things, they are fairly complex to understand or maintain to 
those unfamiliar with MSA. Another is that they can be difficult to implement, and a poor implementation may be worse than
sticking with a functional macroservice. Adoption can also be tricky because the infrastructure is still very new, and 
there aren’t as many resources available as developers may be used to seeing.

  The authors conclude that microservices are not exactly a slam-dunk. Not everyone should adopt them simply because it is 
an industry trend. In fact, most companies do not have the need for the cutting-edge advantages microservices require. 
They go on to give a few recommendations to those who do decide to press forward for adoption. First, the transition 
should be gradual. Don’t rush and translate your entire code base to MSA. Only then should adopters move on to domain-level 
functionality. They have some other recommendations that will not all be reproduced here. The curious reader should 
reference the original document.
