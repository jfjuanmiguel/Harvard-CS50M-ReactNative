# CS50's Mobile App Development with React Native

Notes and practice projects about Mobile Application of Harvard University CS50 course. (Spring 2018)

## Lecture

Lecture|Title / Contents|Slides|Source Code|Project
-------|----------------|------|-----------|-------
[Lecture 0](https://video.cs50.net/mobile/2018/spring/lectures/0)|Overview, JavaScript|[![slides](https://cdn1.iconfinder.com/data/icons/education-set-4/512/presentation-24.png)](http://cdn.cs50.net/mobile/2018/spring/lectures/0/lecture0.pdf)|[![code](https://cdn.iconscout.com/icon/premium/png-24-thumb/code-316-739418.png)](http://cdn.cs50.net/mobile/2018/spring/lectures/0/src0.zip)|-
[Lecture 1](https://video.cs50.net/mobile/2018/spring/lectures/1)|JavaScript, ES6|[![slides](https://cdn1.iconfinder.com/data/icons/education-set-4/512/presentation-24.png)](http://cdn.cs50.net/mobile/2018/spring/lectures/1/lecture1.pdf)|[![code](https://cdn.iconscout.com/icon/premium/png-24-thumb/code-316-739418.png)](http://cdn.cs50.net/mobile/2018/spring/lectures/1/src1.zip)|[Project 0 - TODO App](http://docs.cs50.net/mobile/2018/x/projects/0/project0.html)
[Lecture 2](https://video.cs50.net/mobile/2018/spring/lectures/2)|React, Props, State|[![slides](https://cdn1.iconfinder.com/data/icons/education-set-4/512/presentation-24.png)](http://cdn.cs50.net/mobile/2018/spring/lectures/2/lecture2.pdf)|[![code](https://cdn.iconscout.com/icon/premium/png-24-thumb/code-316-739418.png)](http://cdn.cs50.net/mobile/2018/spring/lectures/2/src2.zip)|-

## Project

Project  |Title   |Example|Remark
---------|--------|-------|-------
Project 0|TODO App|[Ex1](https://github.com/GeekNabil/Todo-VanillaJS/blob/master/script.js), [Ex2](https://github.com/jhhayashi/react-native-course/tree/master/project0/solution)|[Project 0](https://cs50.github.io/mobile/projects/0), [Github Classroom Repository](https://github.com/mobile50/project0-daviddwlee84)

## Notes

### Project 0

* JavaScript Property
  * innerHTML:
    * HTMLDOMObject.innertHTML
    * The Element property innerHTML gets or sets the HTML or XML markup contained within the element.
  * children:
    * It will return a "HTMLCollection" and it can be accessed like an array.
    * [Best way to get child node -- Stackoverflow](https://stackoverflow.com/questions/10381296/best-way-to-get-child-nodes)
  * parentNode:
    * Return its parent node element
  * appendChild

* Delete Element
  * Traditional way
    * `element.parentNode.removeChild(element)`
  * jQuery (DOM Library)
    * `$('#some_element').remove()`
    * [jQuery Remove Element](https://www.w3schools.com/jquery/jquery_dom_remove.asp)

* console.log(Object) will show the object detail on browser's console. (If not familar with the object property it's a good way to find out)

## Links

* [**Mobile App Development with React Native - Spring 2018**](https://cs50.github.io/mobile/)
* [edx - CS50's Mobile App Development with React Native](https://www.edx.org/course/cs50s-mobile-app-development-with-react-native)

> * [Harvard Extension Course](https://www.extension.harvard.edu/)
>   * [Search result for CS50](https://www.extension.harvard.edu/course-catalog/courses?keyword=cs50)
>     * Spring 2019
>       * [CSCI E-33A Web Programming with Python and JavaScript](https://www.extension.harvard.edu/course-catalog/courses/web-programming-with-python-and-javascript/25184?keyword=cs50)
>       * [CSCI E-23A Introduction to Game Development](https://www.extension.harvard.edu/course-catalog/courses/introduction-to-game-development/25183?keyword=cs50)
>       * [CSCI E-1B Computer Science for Business Professionals](https://www.extension.harvard.edu/course-catalog/courses/computer-science-for-business-professionals/25393?keyword=cs50)

* [CS50 Github](https://github.com/cs50)
  * [Mobile50 Github](https://github.com/mobile50) - It will including your private project repository when you use *Github Classroom*. Just fork it to your account.
* Others' Project
  * [dillon/cs50-mobile](https://github.com/dillon/cs50-mobile)
