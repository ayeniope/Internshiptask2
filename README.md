# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### I Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- fontawesome

### What I learnt
I was able to work on responsiveness for the first time.
The aspect of placing a div over the footer was a bit difficult but after reading some articles I was able to get it and I am sure I will be able to tackle such easily in the future.

Below is the section that stressed me most in the project:

```html
 <section class="getting-access">
    <h2>Get early access today</h2>
    <p> It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.</p>
    <form action="#">
      <input type="email" placeholder="example@email.com">
      <input type="submit" value="Get Started for free ">
    </form>
 </section> 
```
```css
.getting-access{
    font-family: sans-serif;
    display: flex;
    flex-direction: column;
    position: absolute;
    text-align: center;
    bottom: -100px;
    left: 50%;
    transform: translateX(-50%);
    justify-content: center;
    padding: 30px 100px;
    background:  hsl(219, 30%, 18%); 
    border-radius: 10px;    
}
**I look forward to learning more on CSS**

link to the live website       https://fylo-landingpage-oa.netlify.app/
