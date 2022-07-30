Fun with CSS
============

Tasks
-----

### 0\. Sprite languages


By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>

```

And this image file: [0-sprite.png](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220730%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220730T041103Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=5f19ebba819a650cfb88368b1f5593df2adc8faadf0f1c638538251f6aa066b1 "0-sprite.png")

Create `0-styles.css` and generate this layout:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220730%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220730T041103Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=31f6cc74c86cbd381660dea386d29c273eac0251b6c7167420746a26fcc45542)

You are not allowed to change the image and the HTML - *sprite is cool!*

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `0-styles.css`



### 1\. Move the (under)line

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>

```

Create `1-styles.css` and generate this layout where the underline is hidden by default and appeared slowly...:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220730%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220730T041103Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cc98f31117a354d3a0300f293a8e735e7150b51c57b7c2c5937d6a29ac126a16)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `1-styles.css`



### 2\. Toggle

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>

```

Create `2-styles.css` and generate this layout where the `<input>` is has this custom toggle layout:

**Checked:**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220730%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220730T041103Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d53fb54abe205ecfdd2c74ab67bc7f8548fcb15f106ffaa549a5487a66240f82)

**Unchecked:**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220730%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220730T041103Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=969e09dd44d55b2510c640a5594836d2869ea11837ef4a7343c1733fc09572b4)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `2-styles.css`

 Done? Help

### 3\. Menu

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>

```

Create `3-styles.css` and generate this layout/animation:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220730%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220730T041103Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4b2dac3d654578deb896167611fc29d2804cd507d2b2537d12200665efaf994a)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository: `alx-frontend-for-fun`
-   File: `3-styles.css`

 Done? Help

Ready for a manual review

Copyright © 2022 ALX, All rights reserved.
