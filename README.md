# BackTopPositionScroll

Hosted Link to WebPage: https://golden-lamington-0098f7.netlify.app/

Reflection: For this assignment I was trying to fix an issue that one of my lecturers was experiencing while shopping online.
She stated that after scrolling through a website and clicks on a button it leads her to a referral page, although, when she goes back to the original website 
the scroll position is forgotten and she loses her original place on the page.

Fix: After some browsing online I found out that jQuery can help me out on that. I had been thinking about the problem of attaching a scroll event but instead I found a setInterval function which helped me solve the issue and now if you scroll,click on Buy Now! from any product cards and go back, you will be lead to the position of scroll you were in(based on the container not the product card). For maximum accuracy one can just change the $(".container") to $(".card") in var target.
