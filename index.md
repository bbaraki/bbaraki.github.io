---
layout: default
---
---
## About Me
Hello, my name is Bruke. I am passionate in understanding how we can make robots more intelligent and enable them to be more collaborators with humans.  

## Table of Contents
<ul class="toc">
  <li><a href="#research">Active Exploration Research</a></li>
  <li><a href="#sparky">Sparky: an Interactive Robotics Kit</a></li>
  <li><a href="#meam517">Coming Soon...</a></li>
</ul>

## Active Exploration Research at DAIRLab UPenn (2024-25)  <a id="research"></a>

Perception, uniquely defined by our human experience, is the multi-modal synthesis of various senses (e.g., visual, auditory, olfactory, and haptic) to enable real-time decision-making. In recent years, both academia and industry have aimed to develop intelligent robots capable of emulating these senses for tasks such as pick-and-place operations, search and rescue missions, and dexterous manipulation. However, touch is an often underestimated perception modality compared to vision, despite the potential benefit from haptic feedback in these real-time tasks. In fact, studies have demonstrated the importantance of touch in fine manupation tasks; for example, lighting a match became nearly impossible for human subjects after their fingertips were numbed. 
 
In this project, I aim to understand how robots can percieve objects through tactile interactions. 

Suppose I gave you an object to explore with your hands while keeping your eyes closed. If asked to describe the object's shape, you might intuitively search for corners and edges. In neuroscience, this behavior is referred to as an _exploratory procedure_. For robots operating in unstructured environments (e.g., the aftermath of a nuclear disaster), perception through computer vision techniques, like depth estimation, shape reconstruction, and object identification, may be impaired by poor lighting and occlusions. To operate effectively in such conditions, robots must understand their surroundings by constructing internal models of objects.

**How can we imbue robots with the intelligence to perform exploratory procedures that promote the acquisition of informative object properties?**



<details class="accordion">
  <summary>Project Details</summary>
  <p>
    <!-- ContactNets created a framework for modeling the discontinuities in contact dynamics.
    $$
    \large
    \begin{equation}
    \frac{M}{\Delta t} (v_{i+1}-v_{i}) = J_{i}^{T} \lambda_{i} - Mg
    \end{equation}
    $$

    Penalize any deviations from Newton's 2nd law. Note that the $M^{-1}$-norm squared is used to maintain units of m/s/s.

    $$
    \large
    \begin{equation}
    l_{1}(x_{i},\lambda_{i})=||M(v_{i+1}-v_{i} -g) - J_{i}^{T} \lambda_{i}||^2_{M^{-1}}  
    \end{equation}  
    $$ -->
  </p>
</details>

---
## Sparky: an Interactive Robotics Kit (2023-24) <a id="sparky"></a>  

Students, motivated by our shared experience of limited access to early STEM education, aimed to address STEM engagement disparities. For our senior design project, we developed Sparky, a hands-on robotics kit that doubles as an affordable, educational assistant. **To enable real-time social interaction, we integrated large language models (LLMs)**.


In this framework, the GPT-4 LLM translated natural language into coordinated robot actions,
including motion, speech, and facial expressions (e.g., ’Hey Sparky, move forward and explain the
water cycle’). I implemented the finite set of actions, sending low-level signals to its arms, face,
and drive train. Furthermore, having designed the hardware (i.e., mechatronic system and circuit
board) myself, I implemented safety features for electric hazards in the assembly process.
The engagement in user testing demonstrated the positive impact of assistive robots on the
human psyche. This experience was very meaningful to me and helped shaped my mission of making intelligent robot partners.

<iframe width="560" height="315" 
        src="https://www.youtube.com/embed/gEysf9Bl_84" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>
---
## Trajectory Optimization for a Unicycle (2023-24) <a id="meam517">   

Stay Tuned ...

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~.

Starting at time $T$, the robot executes a trajectory from $T$ to $T+H$.    
  
Observation with process noise:  
  
The dynamics is described as follows:  


To run the test: sudo bundle exec jekyll serve

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->
