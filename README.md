# EventPoster
A event poster template support `Responsive web design` `(RWD)`.
It fit for desktop and mobile, viewpoint threshold is 768px.
Demo: https://d50000.github.io/EventPoster/

## Devices Viewpoint
Supporting for all device screen width, height.

- use CSS `@media` to toggle the class for different viewpoint.

```
/* For desktop: */
@media only screen and (min-width: 769px) {
    .col-1 {width: 8.33%;}
    .col-2 {width: 16.66%;}
    .col-3 {width: 25%;}
    .col-4 {width: 33.33%;}
    .col-5 {width: 41.66%;}
    .col-6 {width: 50%;}
    .col-7 {width: 58.33%;}
    .col-8 {width: 66.66%;}
    .col-9 {width: 75%;}
    .col-10 {width: 83.33%;}
    .col-11 {width: 91.66%;}
    .col-12 {width: 100%;}

    .Lfloatleft{
        float: left;
    }

    .Lfloatright{
        float: right;
    }

    .navbtn{
        margin-top:4%;
        font-size:2vw;
    }
}
```

```
/* For mobile phones: */
@media only screen and (max-width: 768px) {
    
    .col-m-1 {width: 8.33%;}
    .col-m-2 {width: 16.66%;}
    .col-m-3 {width: 25%;}
    .col-m-4 {width: 33.33%;}
    .col-m-5 {width: 41.66%;}
    .col-m-6 {width: 50%;}
    .col-m-7 {width: 58.33%;}
    .col-m-8 {width: 66.66%;}
    .col-m-9 {width: 75%;}
    .col-m-10 {width: 83.33%;}
    .col-m-11 {width: 91.66%;}
    .col-m-12 {width: 100%;}
}
```

## Relative units
Auto resize with the width and height change.

- use `em` `rem` `vw` `vh` `vmin` `vmax` for the font unit.

```
body{ 
	/* default the font size */
	font-size:16px;
}

.font {
    font-size: 1.2em;       /* 120% font size according to the parent font size */
    font-size: 1.2rem;      /* 120% font size according to the root (body default) font size */
    font-size:2vw;          /* According to the screen width, set set the font size 2% */
    font-size:2vh;          /* According to the screen height, set set the font size 2% */
}
```

- use `percentage (%)` for the unit.

```
img {
    max-width: 100%;
    height: auto;
    text-align: center;
    margin-top:2%;
}
```

