Lesson 0
==
*November 19, 2012*


Please fork this repository, complete any number of the following assignments, and then submit your work as a pull request.
Please submit assignments involving the [FHS Rails Practice repository](https://github.com/aperley/fhs-practice) as pull requests to that repo.

Basic
--

- **HTML**: Keep doing [Codecademy Web Fundamentals Tutorials](http://www.codecademy.com/tracks/web).

- **Programming**: Download and install Ruby or Python and use it to solve the problems in the file called
`basic_programming_challenges.txt` in the basic directory.

- **CSS**: Add a style block to the head of `boring_page.html` to:
    - Remove the underline from all links
    - Center all of the paragraphs
    - Make all the headings 2 times the normal font size (*hint: check out the em unit*), blue, and all capitals.
    - Make the text inside of em tags nested in div tags red:
    
        ```
        <em>This text is not red</em>
        <div>
          <em>This text IS red</em>
        </div>
        ```
    - Give all paragraphs `10px` of padding on all four sides
    - Add an html5 doctype

- **Rails**: Complete Chapter 1 of Michael Hartl's [Ruby on Rails Tutorial](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book).
If you use Windows, set up Rails in an Xubuntu virtual machine.


Intermediate
--

- **HTML/CSS**: Style the `nav` element of `homepage.html` in the intermediate directory so that it is a horizontal navigation bar
like the one on the homepage of fairviewhs.org.  It should indicate the page the user is currently on. Put the stylesheet in a 
separate file called `homepage_styles.css`.

- **HTML/CSS**: Add some more styles to `homepage_styles.css` to make a two column layout (*hint: float the divs*) and make the page look pretty.
CSS is about having an eye for design, so try to make an attractive page.

- **Programming**: Solve the challenges in the file called `intermediate_programming_challenges.md`.

- **Rails**: Fork the [FHS Practice rails application](https://github.com/aperley/fhs-practice) and write routes, controller actions, and
views for the CRUD actions.

- **CSS**: Rewrite `homepage_styles.css` as an `.scss` file and compile it using the [SASS Gem](http://sass-lang.com/).

EXTREME Advanced
--

- **HTML/CSS/JS**: Use the [Yahoo Weather API](http://developer.yahoo.com/weather/) to write a nicely-styled html page that uses **jQuery** to
display the current weather for Boulder, CO.  **Add this file to this repository and submit it as a pull request**.

- **Linux**: On a Linux system, download and build [git](https://github.com/git/git) **from source**.

- **Rails/Capistrano**: Install the capistrano gem and write a recipe to deploy the [FHS Practice rails application](https://github.com/aperley/fhs-practice)
to `example.com`.

- **Rails**: In the [FHS practice application](https://github.com/aperley/fhs-practice) add an `active` boolean attribute to the `student` model
that defaults to true, and then write a `default_scope` so that `Student.all` returns only active students.