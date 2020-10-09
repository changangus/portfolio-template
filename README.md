# Portfolio template
A template for beginner developers to showcase their projects and skills for potential jobs or internships. 

## Getting Started
```bash
# Clone this repository
$ git clone https://github.com/changangus/portfolio-template

# Go into the repository
$ cd portfolio-template

# Remove current origin repository
$ git remote remove origin
```

## Adding your links to github, linkedin etc..
1. Open index.html in your code editor
2. Go to the <!-- Icons Section -->
3.
```
    <ul class="icons">
      <a class="icon" href="#ADD LINK HERE" target="_blank"><i class="devicon-github-plain"></i></a>
      <a class="icon" href="#ADD LINK HERE" target="_blank"><i class="devicon-codepen-plain"></i></a>
      <a class="icon" href="#ADD LINK HERE" target="_blank"><i class="devicon-linkedin-plain"></i></a>
    </ul>
```

4. Go to https://devicon.dev/ for more icon options or include Font Awesome link in the head for more variety 

## Hero and About Me
1. Change it to your name in this span in the hero section
```
<h1 class="main-header">Hi, My name is <span>Your Name</span></h1>
```
2. Describe your title in any way you'd like!
```
<h2 class="sub-header">Some kind of Developer.</h2>
```

3. Describe yourself in the p tag with "class=descripton" in the about me section

```
    <p class="description">HERE</p>
```

## Skills 
1. All icons can be found at https://devicon.dev/ search there for desired icons and add or replace icons by changing the "class" as you wish in the skills section

```
    <div class="skills">
      <h3 class="sub-header skills-header">Skills:</h3>
      <ul class="skills-grid">
        <li class="skills-item"><i class="devicon-html5-plain-wordmark colored"></i></li>
        <li class="skills-item"><i class="devicon-css3-plain-wordmark colored"></i></li>
        <li class="skills-item"><i class="devicon-javascript-plain colored"></i></li>
      </ul>
    </div>
```

## Projects
Go to the project section and you will see a card component surrounded by an achcor tag:

```
# Add the title, link and image as shown below:

      <a href="#ADD LINK TO LIVE PROJECT">
        <div class="card 1">
          <div class="card_image"> 
            <img src="ADD SRC FILE OR URL FOR PROJECT IMAGE" /></div>
          <div class="card_title title-white">
            <p>ADD TITLE HERE</p>
          </div>
        </div>
      </a>
```

## Contact
Find the contact section and supply the necessary info in the shown locations
```
<section class="contact" id="contact">
    <h2 class="sub-header">Contact</h2>
    <a href="mailto:#ADD YOUR EMAIL HERE" class="email-link">YOUR-EMAIL-HERE@email.com</a>
</section>
```

## Deploy!
I recommend using github pages since this is a static site and ghpages is free!

1. Create a repo
2. Use git init in the root file (portfolio-template) 
3. Add your remote origin by following the instructions on the repo page
4. Go the the settings and enable ghpages
5. Start up the link and enjoy your new Portfolio!