# Advizr Express

Advizr Express is a prospecting tool available to current Advizr clients for free. This page will show you how to add the Advizr Express widget to your website. For questions or help, please email support@advizr.com.

The Advizr Express widget supports "responsive" or "mobile optimized" websites, and will resize down to 320px width.

## Installation

Just paste the following code anywhere into your website (make sure to replace YOUR EMAIL ADDRESS with your actual email address):

```html
<div id="AdvizrExpress" data-ctaemail="YOUR EMAIL ADDRESS"></div>
<script src="http://54.88.63.218/build/ext/AdvizrExpressWidget.v1.js"></script>
```

Whatever email you provide in place of YOUR EMAIL ADDRESS, is where you will receive email from Advizr Express, as filled out by
your website's visitors. Make sure to add express@advizr.com to your contacts, to prevent it being marked as spam by your email provider.

For "responsive" or "mobile optimized" websites, it is highly recommended that you allow the container to take up the full 
width of the page, especially at smaller widths (less than 600px). 
In [demo.html](demo.html), you can see this being done by using negative margins to offset the page's padding.

## Customization

You can customize some aspects of the container by using CSS rules that style the `#AdvizrExpress` div. However, be aware that
the minimum height is 650px at widths >= 800, and 850px at widths < 800px. This will be automatically applied, and cannot be overwritten.

## Demo

Take a look at [demo.html](demo.html)

## Help

For questions or help, please email support@advizr.com.