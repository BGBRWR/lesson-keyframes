# lesson-keyframes

##objective
We're going to try to replicate this: https://spencerkekauoha.github.io/lesson-waves-keyframes/
We're going to do it with only using css, and we'll learn how to use @keyframes. http://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp

##step one
create a index.html file.
create a style.css file.

#step two
 add both css files to your html.
 *index.html*
 `   <link rel="stylesheet" href="reset.css" media="screen" title="no title">
     <link rel="stylesheet" href="style.css" media="screen" title="no title">
`
make sure the last linked css file is the one you want to have the final say.

#step three
add the images in the img folder to the index.
  `<section class="wave-container">
      <div class="backwave">
        <img src="/img/great_wave_backwave.png" alt="wavy wavy" />
      </div>
      <div class="frontwave">
        <img src="/img/great_wave_frontwave.png" alt="wavy wavy" />
      </div>
    </section>`

#step four
