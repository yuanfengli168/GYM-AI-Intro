- how to select the id? 
    - using `#`.
- how to select by class?
    - using `.`.
- how to add an image as background? 
    - no tag in html needed, just create a div, and in CSS, use: `background-image: url('https:.....')`.
- what is justify-content?
    - center will make left and right evenly distributed. [MDN link](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)
- what is align-items?
    - center, vertically centered. [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)
- what is text-align?
    - Align texts horizontal alignment. [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
- how to create gaps between flex items?
    - adding `gap: 20px` in the CSS.
- what does `display: none` do?
    - make things disappear. [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/display).
- How to make the size to 100% of the screen no matter how you resize? 
    - `heigt: 100vh; width: 100vw;`
- what does `gap` do? 
    - in `flex`, defines the gap between items.
- how to make the background image responsive by vh/vw, but not showing replications? 
    - e.g.: 
    ```
    #gym_ai_intro {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
        url('https://img1.wsimg.com/isteam/stock/606/:/rs=w:2560');
        background-size: 100%;
        width: 100vw;
        height: min(100vh, calc(100vw * (1122 / 1683)));
    }
    ```
- How to adjust font size based on viewport size?
    - Not read yet, maybe finish it later. [potential doc](https://enzedonline.com/en/tech-blog/create-responsive-font-sizes-based-on-the-viewport/)