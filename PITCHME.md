## The Kitchen Sink
##### <span style="font-family:Helvetica Neue; font-weight:bold">A <span style="color:#e49436">Git</span>Pitch Feature Tour</span>

---

## Slideshow Theme Switcher
<span style="font-size:0.6em; color:gray">Available bottom-left of screen.</span> |
<span style="font-size:0.6em; color:gray">Start switching themes right now!</span>

---

## Tip!
For best viewing experience press **F** key to go fullscreen.

---

## Markdown Slides
<span style="font-size:0.6em; color:gray">Press Down key for details.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slide-Markdown" target="_blank">GitPitch Wiki</a> for details.</span>


+++

#### Use GitHub Flavored Markdown
#### For Slide Content Creation

<br>

The same tool you use to create project **READMEs** and **Wikis** for your Git repos.

---

## Code Slides
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Code-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Use Markdown Code Blocks

<br>

And enjoy code syntax highlighting for dozens of languages powered by <a target="_blank" href="highlight.js](https://highlightjs.org">highlight.js</a>.

+++

```JavaScript
// JavaScript Code Block

$('button').click(function(){
    $('h1, h2, p').addClass('blue')
    $('div').removeClass('important')
    $('h3').toggleClass('error')
    $('#foo').attr('alt', 'Lorem Ipsum')
});
```

+++

```Scala
// Scala Code Block

HashMap params = HashMap(n -> 10, mean -> 5)

// Define executable for R stats#rnorm function call.
OCPUTask task = OCPU.R()
                    .pkg("stats")
                    .function("rnorm")
                    .input(params.asJava)
                    .library()
```

+++

```Go
// Go Code Block

package main

import "fmt"

func swap(x, y string) (string, string) {
    return y, x
}

func main() {
    a, b := swap("hello", "world")
    fmt.Println(a, b)
}
```

---

## GIST Slides
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/GIST-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### GitHub GIST
#### Building Blocks For Any Presentation

<br>

Enjoy 100% reusable code snippets, excellent syntax highlighting, code indentation and styling. 

+++?gist=8da53731fd54bab9d5c6

+++?gist=28ee3d19ddef9d51b15adbdfe9ed48da

---

## Image Slides
## [ Inline ]
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Image-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Make A Visual Statement

<br>

Use inline images to lend a *visual punch* to your slideshow presentations.


+++

<span style="color:gray; font-size:0.7em">Inline Image at <b>Absolute URL</b></span>

![Image-Absolute](https://d1z75bzl1vljy2.cloudfront.net/kitchen-sink/octocat-privateinvestocat.jpg)

<span style="color:gray; font-size: 0.5em;">the <b>Private Investocat</b> by <a href="https://github.com/jeejkang" target="_blank">jeejkang</a></span>


+++

<span style="color:gray; font-size:0.7em">Inline Image at GitHub Repo <b>Relative URL</b></span>

![Image-Absolute](assets/octocat-de-los-muertos.jpg)

<span style="color:gray; font-size:0.5em">the <b>Octocat-De-Los-Muertos</b> by <a href="https://github.com/cameronmcefee" target="_blank">cameronmcefee</a></span>


+++

<span style="color:gray; font-size:0.7em"><b>Animated GIFs</b> Work Too!</span>

![Image-Relative](https://d1z75bzl1vljy2.cloudfront.net/kitchen-sink/octocat-daftpunkocat.gif)

<span style="color:gray; font-size:0.5em">the <b>Daftpunktocat-Guy</b> by <a href="https://github.com/jeejkang" target="_blank">jeejkang</a></span>

---

## Image Slides
## [ Background ]
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Make A Bold Visual Statement

<br>

Use high-resolution background images for maximum impact.

+++?image=https://d1z75bzl1vljy2.cloudfront.net/kitchen-sink/victory.jpg

+++?image=https://d1z75bzl1vljy2.cloudfront.net/kitchen-sink/127.jpg


---

## Video Slides
## [ Inline ]
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Video-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Bring Your Presentations Alive

<br>

Embed *YouTube*, *Vimeo*, *MP4* and *WebM* inline on any slide.

+++

![YouTube Video](https://www.youtube.com/embed/dNJdJIwCF_Y)

+++

![Vimeo Video](https://player.vimeo.com/video/125471012)

+++

![MP4 Video](http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4)


---

## Video Slides
## [ Background ]
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Video-Slides#background" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Maximize The Viewer Experience

<br>

Go fullscreen with *MP4* and *WebM* videos.

+++?video=http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4

---

## Math Notation Slides
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Math-Notation-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

+++


#### Beautiful Math Rendered Beautifully

<br>

Use *TeX*, *LaTeX* and *MathML* markup powered by <a target="_blank" href="https://www.mathjax.org/">MathJax</a>.

+++

`$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$`

+++

`\begin{align}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{align}`

+++

##### The Cauchy-Schwarz Inequality

`\[
\left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
 \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\]`

+++

##### The probability of getting \(k\) heads when flipping \(n\) coins is:

`\[P(E) = {n \choose k} p^k (1-p)^{ n-k} \]`

+++

##### In-line Mathematics

This expression `\(\sqrt{3x-1}+(1+x)^2\)` is an example of an inline equation.

---

## Slide Fragments
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Fragment-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Reveal Slide Concepts Piecemeal

<br>

Step through slide content in sequence to slowly reveal the bigger picture.

+++

- Java
- Groovy     <!-- .element: class="fragment" -->
- Kotlin     <!-- .element: class="fragment" -->
- Scala     <!-- .element: class="fragment" -->
- The JVM rocks! <!-- .element: class="fragment" -->

+++

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>25</td>
  </tr>
  <tr class="fragment">
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr class="fragment">
    <td>John</td>
    <td>Doe</td>
    <td>43</td>
  </tr>
</table>

---
## <span style="text-transform: none">PITCHME.yaml</span> Settings
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slideshow-Settings" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Stamp Your Own Look and Feel

<br>

Set a default theme, custom logo, custom css, background image, and preferred code syntax highlighting style.

+++

#### Customize Slideshow Behavior

<br>

Enable auto-slide with custom slide intervals, presentation looping, and RTL flow.


---
## Slideshow Keyboard Controls
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slideshow-Fullscreen-Mode" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Try Out These Great Features Now!

<br>

| Mode | On Key | Off Key |
| ---- | :------: | :--------: |
| Fullscreen | F |  Esc |
| Overview | O |  O |
| Blackout | B |  B |
| Help | ? |  Esc |


---

## GitPitch Social
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Slideshow-GitHub-Badge" target="_blank">GitPitch Wiki</a> for details.</span>

+++

#### Slideshows Designed For Sharing

<br>

- View any slideshow at its public URL
- [Promote](https://github.com/gitpitch/gitpitch/wiki/Slideshow-GitHub-Badge) any slideshow using a GitHub badge
- [Embed](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Embedding) any slideshow within a blog or website
- [Share](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Sharing) any slideshow on Twitter, LinkedIn, etc
- [Print](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Printing) any slideshow as a PDF document
- [Download and present](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Offline) any slideshow offline

---

## GO FOR IT.
## JUST ADD <span style="color:#e49436; text-transform: none">PITCHME.md</span> ;)
