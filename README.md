# Higher Order Components

Using higher order components allows us to write functions that take in components, and return components with added functionality.  The technique can become very useful in the context of authorization -- where we only allow a user to view certain pages or take certain actions if he has the correct permissions or role.

### Higher Order Components

First, read about higher order components to see how they function and in which cases they are preferred over other techniques.

* [Higher Order Components Intro](https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750)
* [Higher Order Components](https://www.sitepoint.com/react-higher-order-components/)

### Higher order components and authorization

Use of higher order components can be applied to solving a problem of authorization.  Remember that authorization states, given that we know who you are, this is what you are allowed to do.  So in the context of a web application, it generally means user permissions to view or take action on certain web pages.  Take a look at the following blog posts, which describe how higher order components can be used to solve the problem of authorization in react and redux application.

* [Higher order components](http://engineering.blogfoster.com/higher-order-components-theory-and-practice/)
* [Higher Order Components with Currying](https://hackernoon.com/role-based-authorization-in-react-c70bb7641db4)
<p class='util--hide'>View <a href='https://learn.co/lessons/higher-order-components'>Higher Order Components</a> on Learn.co and start learning to code for free.</p>
