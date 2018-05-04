# Domain-Driven Design Implementation In PHP

This is a working demo which demonstrates how to implement DDD in PHP.

I followed this [blog post](https://www.yordipauptit.com/hexagonal-architecture-in-php/) by [Yordi Pauptit](https://github.com/YP28).

I have a bit different approach, I wrapped the  `Domain`,`Application` and `Infrastructures` folders or layers in the Domain itself. In my mind  this is more organized and self contained than scattering say for example everything related to `Post` domain into  `Domain`,`Application` and `Infrastructures` directories.



