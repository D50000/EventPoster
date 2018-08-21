# EventPoster
A event poster template support `Responsive web design` `(RWD)`.
It fit for desktop and mobile, viewpoint threshold is 768px.

##Devices Viewpoint
Supporting for all device screen width, height.
	-use CSS @media to toggle the class for different viewpoint.

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
@media only screen and (max-width: 768px) {
    /* For mobile phones: */
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

##Relative units

	-
	```
	```
