# Cohort Dance Party!
It's a dance party, and you're invited! (If by "dance party," we mean "building something in JavaScript.")

### Your instructions
1. Make a JavaScript call to the WynPics API -- the documentation is below -- to fetch all the headshots from your cohort and populate the `index.html` page.
2. Everything should be contained within the `<main></main>` HTML tags.
3. There should be a `<div class="student"></div>` block for every student.
4. Use an `<h3></h3>` tag to display the student's first and last name.
5. When using an `<img>` tag for the student photo, but don't forget to include the student's full name in the `alt=""` attribute.

### Bonus challenges
 * (Challenge: MEDIUM) Sort all the students by last name before they appear on the page.
 * (Challenge: REALLY HARD) Hey, you notice that Will Smith "Miami" MP3 in the GitHub repo? Wouldn't it be crazy if you used JavaScript to dynamically create an HTML5 `<audio>` tag using `document.createElement` and had it, like, play when you moused over an image, [just like this 404 page](https://bluegg.co.uk/404) when you click on Will Smith's head? [That'd be wild.](https://css-tricks.com/play-sound-on-hover/)

#### Credits
CSS provided by OG WebDev instructor Andy Weiss

## The WynPics API
### GET /cohorts/[id]
Example: https://wynpics.herokuapp.com/cohorts/[id]

`[id]` is the Wyncode Cohort number. For example, if you enrolled in the Wyncode Full-stack Web Developer course in January 2020, you're in Cohort 36.

Response body:
```
[
    {
        "firstName": "Juha",
        "lastName": "Mikkola",
        "imageUrl": "http://wynpics.herokuapp.com/Staff/MikkolaJuha.jpg"
    },
    {
        "firstName": "Johanna",
        "lastName": "Mikkola",
        "imageUrl": "http://wynpics.herokuapp.com/Staff/MikkolaJohanna.jpg"
    }
]
```
