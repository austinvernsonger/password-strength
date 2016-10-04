# password-strength
In this tutorial, [Solodev]() will show you how to test the strength of a password utilizing [strength.js by Aaron Lumsden](http://jquerycards.com/forms/inputs/strength-js/) and can be utilized on your own website's registration page to inform users of the strength of their chosen password.

##  Tutorial

View detailed instructions in Solodev's [Creating a Password Strength Indicator](https://www.solodev.com/blog/web-design/creating-a-password-strength-indicator.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/56p026Lf/).

## HTML

The password strength indicator contains the following basic HTML markup.

```
<h1><span>Password</span> Strength</h1>
<p>Test the strength of your password below.</p>
<form id="myform" action="" method="get" accept-charset="utf-8">
   <input id="myPassword" type="password" name="" value="">
</form>
```

## CSS

All required CSS is in password-strength.css

## External Includes

This tutorial requires the following third party resources.

```
<link href='http://fonts.googleapis.com/css?family=Lato:400,700' rel='stylesheet' type='text/css'>
<link href="password-strength.css" rel="stylesheet">

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://www.solodev.com/assets/password/strength.js"></script>
```
