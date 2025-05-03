+++
title =  "Home"
type = "home"
draft = false
+++


{{< showcase-section
    title="Hello, I'm Lisa."
    subtitle="E-Learning Specialist & Instructional Designer"
    buttonText="Email"
    description="Based in Switzerland, I work at ..."
    imgSrc="images/showcase/showcase.png"
    imgScale="0.5"
 >}}

{{< platform-links >}}
    {{< link icon="linkedin" url="https://www.linkedin.com/in/lisa-siegrist-503236122/" >}}
    {{< link icon="square-github" url="https://github.com/siegristlk" >}}
    {{< link icon="youtube" url="#" >}}
    {{< link icon="instagram" url="https://www.instagram.com/lisasiegrist" >}}

{{< /platform-links >}}

{{< /showcase-section >}}

{{< about-section
    title="Who am I?"
    content="Eine Problemlöserin von Herzen.... This content is using the <code>about-section</code> shortcode. <br/>You can write <code>HTML</code>, as long as you <em>wrap it</em> accordingly. "
    button_icon="icon-user"
    button_text="You can edit the text, link and icon"
    button_url="https://www.google.com"
    imgSrc="images/about/user-picture.png"
    imgScale="0.5"
 >}}

{{< education-list
    title="Formal Education (education-list)" >}}

{{< experience-section
    title="My job experience (title)"
    intro_title="Intro (intro_title)"
    intro_description="Ich weiss noch nicht was ich hier schreiben soll, aber das ist ein Test. Description (intro_description).<br>You can use HTML,with <strong>strong</strong> formatting, or lists <ul><li>one</li><li>two</li></ul>" 
    button1_url="https://example.com"
    button1_text="Visit Example"
    button1_icon="icon-globe"
    button2_text="All experience"
    button2_url="/experience"
    button3_text="Button #3"
    button3_url="/experience"
>}}

{{< experience-list
    title="Experience (as list)"
    padding="false" >}}

{{< client-and-work-section
    title="A selection of my work" >}} 

{{< testimonial-section
    title="What they say about me" >}}

{{< spacer size="large" >}}

## Extra home content

Additional content added after the `section` blocks, in the `home.md` file. 

Here you could freestyle, add other shortcodes, ...  Or just let the content empty, and rely on the shortcode sections alone.

{{< spacer size="small" >}}

{{< text-section
title="Extra (centered) content"
centered="true"
>}}

You can also use the `text-section` shortcode to add centered texts

{{< /text-section >}}
