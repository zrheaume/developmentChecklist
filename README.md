# Web App Development Checklist

## Scope
**The way we approach any web application, an online store in this case, is entirely dependent on the scope of the application**
*Elements of scope to consider*
   - What is the primary goal
   - What is going to be the central focus (specific product, service, brand, etc...)
   - Who will be the primary user(s)
   - How is the user experience (UX) going to flow (i.e. what will the 'typical' interaction between the user and the service look like)

Within the topic of scope, there are other things still that we have to consider before a line of code is written.
   - Where will the app be deployed (Domain hosting service like godaddy or heroku, amazon webservices, private cloud)
      + *Note: Different hosting options come with drastically different pricetags, but the price is often reflected in superior service*
   - What mechanisms must be put in place to ensure that sensitive information such as billing and shipping information is stored securely
      + *Similarly, it is prudent to note that there are companies that will do all of this sensitive data handling __for you.__ This does ultimately affect the price tag, though*
   - How much traffic can this page be expected to receive?
      + *This often changes over the life of an online application. A big opening week/month that produces heavy traffic could shut down the server if there is no mechanisms in place to plan for that scenario*

Luckily, those are questions mostly for the *devloper* and not for the product owner.
The product owner is more likely responsible for making decisions regarding:
   - UI/UX design - What is the visual and experiential **theme** of the app? Muted pastels and a simple layout, or verbose neons and a page chock-full of features?
   - Content - *THIS ONE'S HELLA IMPORTANT*     What will be the actual content of the site? Besides a list of products, which is an obvious answer, there are more content-laden elements to a page. Will there be "About", "Contact", "Support", "Account", or other pages? What will be the content of these?
   - Functionality - Where should money go once payment has been processed? How should active orders be relayed to someone who can handle the order? How can the service be notified when the item has been sent? Questions like these are critical, but require cooperative brainstorming between the development team and the product owner. 