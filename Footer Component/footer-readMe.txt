Strange behavior of 'sticky':

I notice that body height is given as 200px, footer height I see as 148px and 
I specified top as 100px. But still footer fits exactly inside the body 
without overflow. It seems like top value is being calculated based on the 
available space above the footer while keeping the body height in 
consideration.

When there's not enough space above the footer, browsers might adjust the 
sticky behavior, ensuring that the footer doesn't overflow the container. 
It appears that the browser is making the necessary adjustments to fit the 
footer within the available space, even if the top value technically exceeds 
that space.