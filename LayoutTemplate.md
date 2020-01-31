# Layout
A layout template for Markdown note as a table to list items. The template illustrates how to use icon status, refer resources. See the below example for more detailed information.

-----

## Your Defined Title

|Status|Year|Topic|Comments|
|:----:|:---|:----|:-------|
| ![Completed][Completed]     | Dec 2019 | [Getting Started With Redux]                 | [Dan Abramov] - [egghead.io]  |
| ![Completed][Completed]     | Oct 2019 | [You Don't Know JavaScript]: Types & Grammar | [Kyle Simpson]                |
| ![In Progress][In Progress] |          | [JavaScript and React for Developers]        | [Cassidy Williams] - [Udemy]  |
| ![Soon][Soon]               |          | Read JavaScript: The Good Parts              | Douglas Crockford             |

[//]: # (this is the syntax for Markdown comments which is most platform independent)

[//]: # (Status images)

[Completed]: imgs/done.png "Completed"
[In Progress]: imgs/wip.png "In Progress"
[Soon]: imgs/planning.png "Soon"

[//]: # (Reference links to Topics)

[Getting Started With Redux]: https://egghead.io/courses/getting-started-with-redux
[JavaScript and React for Developers]: https://www.udemy.com/js-and-react-for-devs/
[You Don't know JavaScript]: https://github.com/getify/You-Dont-Know-JS

[//]: # (Reference links to tutors)

[Dan Abramov]: https://twitter.com/dan_abramov
[Kyle Simpson]: https://twitter.com/getify
[Cassidy Williams]: https://twitter.com/cassidoo
[Udemy]: https://www.udemy.com
[egghead.io]: https://egghead.io/

----

## Resources

| Path of Resource|Author|
|:----------------|:----:|
| [33 concepts every JavaScript developer should know] | [Leonardo Maldonado] |
| [Best JavaScript books, tutorials, courses & videos] | [ReactDOM]           |

[//]: # (Reference links to paths)

[33 concepts every JavaScript developer should know]: https://github.com/leonardomso/33-js-concepts
[Best JavaScript books, tutorials, courses & videos]: https://reactdom.com/blog/javascript-books

[//]: # (Reference links to authors)
[Leonardo Maldonado]: https://github.com/leonardomso
[ReactDOM]: https://reactdom.com