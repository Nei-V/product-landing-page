1. More usage of flexbox, is unidimensional (unlike css grid that is bi-dimensional), so the direction (row, column) afects the main axis


2. using semantic HTML, for example nav, sections

3. using links, input and buttons.
in order to use a button as a link you have a few options, in this case I use onclick (javascript). you should't use <a> around a <button> or inside it (even if it works). also, using link as a button is not recommended because of accesibility issues. as an alternative you can use a <button> in a <form> .

4. Usage of media queries. Their order in the css file is important, they have to come after the defined elemens, and if more media queries affect the same element their order is also important.

5. more use of variable properties in css

6. using min-width of fix width on elements to prevent minimizing window.

7. using nowrap in flexbox to prevent colapsing to the next row

8. more using of svg and playing with sizes and viewbox

9. inserting video - you can use a <video> tag if you link to a file, for youtube you have to use iframe.