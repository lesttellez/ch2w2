# ch2w2

in this project i am making my profile.

i started with the header and navigation buttons
below the header

in the html, i created a header to hold my nav elements.

html (header):
<body>
  <header>                                              
      <h1> Celeste Tellez</h1>
      <nav>
          <ul>
            <li>
             <a href="#About-Me"
             ...

in css, i broke down the header elements inorder to disired display

css (header):
header {
    padding:30px;
    font-family:Ar
    ...

header h1 {
    display: inline-block;
    font-size
    ...

header nav {
    padding: 15px;
    margin-right: 20px;
    float: right;
    ...

header nav ul {
    list-sty
    ...

header nav ul li {
    display: inline-f
    ...
----------------------------------------------------------------------
under header I add banner. i utilized div and class to have the banner display

hmtl:
 <div class="banner"></div>

css:
.banner {
    height:300px;
    width: 100%;
    ...

-----------------------------------------------------------------------
under the banner, i createdd a section to hold an image and information that goes across the page
i utilized the div, section, img, and paragraph elements to accplish this.

html:
<div class="content">
        <section id="About-Me">
        <img src="
        ...


css:
.content {
    width:75%;
    display
    ...

p{
    font-size: 15px;
}

#About-Me {
    margin-bottom:60px;
    padding:40px;
    ...

.section {
 margin: 30px;
 width: 100%;
 ...
----------------------------------------------------------------------
below that about me section, i created 2 aligned boxes that hold the work and resume information

html:
<main>
      <section>
        <div id="Work" class="Work">
          <h3>Work</h3>
            <img
              src="./assets/images/projecthoriseon.png" class="float-right"
              alt="
              ....

css:
main {
    display: inline-flex;
}

main section div p{
    font-size: 35px;
}

main section {
    display: flex;
    justify-content: space-between;
    padding: 60px;
    margin: 30px;
    width: 50%;
    ....


----------------------------------------------------------------------
i went ahead and created a footer, that hold my contact information
i used the id inorder to link the element to the header element whih will direct the user to the footer.

html:
<footer>
      <section>
        <div id="contact">
       <h5>Contact
       ...

css:
footer {
    padding:30px;
    font-family:Arial, Helvetica, sans-serif;
    background-color:
    ....

