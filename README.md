Change Text Gredient:
.CLASS_NAME {
    background: linear-gradient(to right, #f12711, #f5af19);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}




/*
======== 
variables 
========
*/
:root {
    --mainBlack: #222;
    --mainWhite: #fff;
    --offWhite: #f7f7f7;
    --darkGrey: #afafaf;
    --mainTransition: all 0.3s linear;
    --mainSpacing: 0.2rem;
    --primaryColo: #FB88B4;
}

/* 
=======
global 
=======
 */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html,
body {
    font-family: "Poppins", sans-serif;
    font-size: 16px;
}

img {
    width: 100%;
    display: block;

}

h1,
h2,
h3 {
    text-transform: capitalize;
    letter-spacing: var(--mainSpacing);
    margin-bottom: 1.25rem;
}

h1 {
    font-size: 3rem;
}

h2 {
    margin-bottom: 0;
}

p {
    font-weight: 300;
    font-size: 0.7rem;
    line-height: 2;
}
