HomeBuilder WordPress
===

Installation
===

WordPress
---

The most valuable resource on how to install WordPress on your local server or production server is Codex. The WordPress bible, visit [WordPress Installation](http://codex.wordpress.org/Installing_WordPress) to learn all the details about WordPress installation.

### Local Server
Learn how to setup local development machine and install WordPress.

<iframe width="560" height="315" src="https://www.youtube.com/embed/AIPrWDw0PzE" frameborder="0" allowfullscreen></iframe>

### Production Server
Learn how install WordPress in production server.

<iframe width="560" height="315" src="https://www.youtube.com/embed/5O5pyFS4VTA" frameborder="0" allowfullscreen></iframe>

*Both tutorials by WP Beginner*


Theme
---

You can install *HomeBuilder WordPress theme* using default theme installer or using FTP. Here is a list of requirements to install *HomeBuilder WordPress Theme* on your server.

### Server Requirements

Minimum server requirements to run **HomeBuilder WordPress Theme** on your server:

* PHP Version: 5.4
* MySQL Version: 5.0
* WordPress Version: 4.0

Theme Options
===

*HomeBuilder WordPress Theme* has very intuitive and rich theme options panel. You can control almost everything from theme options panel.

![HomeBuilder Theme Options](http://i.imgur.com/EnA7cXf.png)


General
---

![HomeBuilder General Options](http://i.imgur.com/XGdYDLK.png)

1. **Display BackToTop:** you can easily on/off back to top button by toggling the switch.


Header
---

![HomeBuilder Header Options](http://i.imgur.com/yWPLe1j.png)

1. **Default Logo:** add your brand identity or logo here (HomeBuilder WordPress Theme doesn't resize or scale your logo so make sure to keep it in good shape).
2. **Retina Logo:** add the retina version of your brand logo (HomeBuilder WordPress Theme doesn't resize or scale your logo so make sure to keep it in good shape).
3. **Header Layout:** choose header layout to display header on each page through the site. Available options are:
  * Default
  * Boxed
  * Transparent
4. **Display Top Bar:** you can disable the top bar form from header by just switching off the button.


Page
---

![HomeBuilder Page Options](http://i.imgur.com/R2e3ZN5.png)

1. **Title Layout:** choose page title layout for all pages through the site.
2. **Sidebar Layout:** select sidebar option for pages only form dropdown and the available options are *Sidebar Left*, *Sidebar Right* and *No Sidebar*.


Service
---

![HomeBuilder Service Options](http://i.imgur.com/hnVo9Cf.png)

1. **Title Layout:** choose page-title layout for all service related pages.
2. **Service Logo:** add your service logo here to display on a sidebar on the single service page. (Default: your barnd logo will be appear)


Blog
---

![HomeBuilder Blog Options](http://i.imgur.com/RNtuG3v.png)
![HomeBuilder Blog Options](http://i.imgur.com/vmbdnoY.png)

1. **Blog Title:** set your blog home page title text.
2. **Title Layout:** choose page-title layout for all blog related pages.
3. **Title Background:** Select an image as a background image for blog page title.
4. **Sidebar:** select sidebar option for blog only form dropdown and the available options are *Sidebar Left*, *Sidebar Right* and *No Sidebar*.
5. **Date Format:** customize your post date format..
6. **Custom Text:** change read more button text.
6. **Excerpt Length:** change excerpt length.


Social Media
---

![HomeBuilder Social Media](http://i.imgur.com/XZCj5SE.png)

1. **Media:** you've unlimited possibilities, you can add almost all the social media links with icons. Just select the media name from dropdown and add your media link in link field.
2. **Link:** place your media link here.


Footer
---

![HomeBuilder Footer Options](http://i.imgur.com/BThQuIk.png)

1. **Widget Area Columns:** select number of columns for footer widget area.
2. **Display Copyright:** switch on to display footer copyright information. If you switch on then you'll be shown a textarea to add copyright information.
3. **Copyright Content:** add copyright content here.


Custom Code
---

### JavaScript
![HomeBuilder Custom JavaScript](http://i.imgur.com/jxtDriP.png)

1. Add your custom JavaScript in that field.

### CSS
![HomeBuilder Custom CSS](http://i.imgur.com/ObzsmYa.png)

1. Add your custom CSS in that field.


Backup
---

![HomeBuilder Backup](http://i.imgur.com/lcn26fJ.png)

1. Copy and paste your backup data here and then click on **Import a Backup** button.
2. These arbitrary texts are actually your theme options data. You can save these text for later use as backup.



Shortcodes
===


Accordion
---

![Accordions shortcode](http://i.imgur.com/p1cgMX9.png)

1. **Mode:** choose accordions mode from dropdown & the available options are:
  * Collapse
  * Toggle
2. click to add accordion item.
3. **Title:** add item title from here.
3. **Content:** add item content from here.
3. **Expand Item?:** choose if want dispaly this item as expanded by default or not.

Alert
---

![Alert shortcode](http://i.imgur.com/kFtAUVp.png)

1. **Alert Type:** choose alert type from dropdown & the available options are:
  * Information
  * Success
  * Warning
  * Danger
2. **Alert Message:** alert message content goes here.
3. **Background Style:** choose alert background style from dropdown & the available options are:
  * None
  * Fill
4. **Display Icon:** click on checkbox to add an icon.
5. **Display Close Button:** click on checkbox to show close button

#### Example:
```
[bucket_alert]Alert message goes here.[/bucket_alert]
```

Banner
---

![Banner shortcode](http://i.imgur.com/6xTgA57.png)

1. **Size:** choose banner size from dropdown & the available options are:
  * Full Screen
  * Half Screen
2. **Auto Play:** click this box to disable/enable the banner autoplay.
3. Click here to add banner item. You can add banner item as much as want to dispaly.

#### Example:
```
[bucket_banner][/bucket_banner]
```

Blog
---

![Blog shortcode](http://i.imgur.com/qLlrmJB.png)

1. **Total Posts** add number of posts want to display.
2. **Speed:** add duration of animation between slides of blog posts.
3. **Autoplay:** click this box to enable/disable autoplay of posts slide.

#### Example:

```
[bucket_blog]
```

Button
---

![Button shortcode](http://i.imgur.com/csII9D2.png)

1. **Button Color:** choose button color from dropdown & the available options are:
  * Theme Color
  * Black
  * White
  * Primary
  * Info
  * Success
  * Warning
  * Danger
2. **Button Size:** choose button size from dropdown & the available options are:
  * Large
  * Medium
  * Small
  * Tiny
3. **Button Text:** button text goes here.
4. **Button Link:** button link goes here.
5. **Open Link In A New Tab:** click on checkbox to open link in a new tab.
6. **Dispaly Icon:** click on checkbox to add an icon.
7. **CSS Class:** button CSS class goes here.

#### Example:

```
[bucket_button]
```

Carousel
---

![Carousel shortcode](http://i.imgur.com/PujeLEl.png)

1. **Style:** choose carousel style from dropdown & the available options are:
  * Style One
  * Style Two
2. **Auto Play:** check this box to enable/disable carousel autoplay.
3. **Speed:** add duration of animation between slides of blog posts.
4. Click to add carousel item.

#### Example:

```
[bucket_carousel][/bucket_carousel]
```

Call To Action
---

![Call to action shortcode](http://i.imgur.com/6TNZ71m.png)

1. **Title:** add title here. 
2. **Subtitle:** add subtitle here.
3. **Button Text:** add button text here.
4. **Button Link:** add button link here.

#### Example:

```
[bucket_cta btn_text="Button Text" subtitle="Subtitle Comes Here" btn_link="#"]SOME TITLE CONTENT[/bucket_cta]
```

Darwin Image
---

![Darwin Image shortcode](http://i.imgur.com/fNtLiWM.png)

1. **Before Image:** add an image to dispaly as before image. 
2. **After Image:** add an image to dispaly as before image. 

#### Example:

```
[bucket_darwin_image before="321" after="317"]
```

Featured Box
---

![Featured Box Shortcode](http://i.imgur.com/DgZgLkn.png)

1. **Featured Box:** choose box style from dropdown & the available options are:
    * General
    * General - Right Align
    * Icon Box - Top
3. **Title:** add featured title here.
4. **Content Size:** choose content text size from dropdown & the available options are:
    * Small
    * Medium
    * Large
5. **Media Type:** choose media type from dropdown & the available options are:
    * Icon
    * Image
6. **Icon:** add featured icon. 
7. **Media Size:** choose media size from dropdown & the available options are:
    * Default
    * Large

#### Example:

```
[bucket_featured_box]
```

Featured Group
---

![Featured Group shortcode](http://i.imgur.com/S1M538Q.png)

1. Click to add item on featured group.
2. **Title:** add featured item title here.
3. **Content:** add featured content here.
4. **Media Type:** choose media type from dropdown & the available options are:
  * Icon
  * Image
5. **Icon:** add an icon from here.

#### Example:

```
[bucket_featured_group][/bucket_featured_group]
```

Heading
---

![Heading shortcode](http://i.imgur.com/zRrYcm5.png)

1. **Heading** choose heading style from dropdown & the available options are:
    * Side Border
    * Bottom Border
2. **Title:** add heading title here.
3. **Subtitle:** add heading subtitle here.
4. **Title Size:** choose title size from dropdown & the available options are:
  * Extra Large
  * Large
  * Medium
  * Small
  * Extra Small
  * Mini

#### Example:

```
[bucket_heading]SOME HEADING TEXT[/bucket_heading]
```

Portfolio
---

![Portfolio shortcode](http://i.imgur.com/xCF6XF3.png)

1. **Portfolio Category:** select portfolio categories by clicking checkbox.
2. **Grid Settings:** choose grid settings from dropdown & available options are:
  * Grid 2
  * Grid 3
  * Grid 4
3. **Items:** add number of portfolios you want to display.
4. **Masonry View:** click on checkbox to enable masonry view.
5. **Gutter Settings:** choose gutter settings from dropdown & available options are:
  * Grid Without Gutter
  * Grid With Gutter
6. **Disable Portfolio Filter:** click on checkbox to disable portfolio filter by tag.


#### Example:
```
[bucket_portfolio grid="four" max_items="6" has_masonry="true" has_gutter="1" filter="true"]
```

Progressbars
---

![Progressbar shortcode](http://i.imgur.com/7hlaieS.png)

1. **Progressbar Style:** choose progressbar stlyle form dropdown & the available options are:
  * Default
  * Inner Text
2. **Content:** progressbar content goes here.
3. **Percentage:** Add progress percentage here (without "%" sign).
4. **Size:** choose progressbar size only (not text size) from dropdown & the available options are:
  * Extra Large
  * Large
  * Medium
  * Small
  * Extra Small
  * Mini

##### Example:
```
[bucket_progressbar type="two" size="h-1x"]Progressbar Content[/bucket_progressbar]
```

Project Information
---

![Project Information shortcode](http://i.imgur.com/HrnFU3b.png?1)

1. Click to add project/service information item
2. **Name:** add information/item name here.
3. **Content:** add information/item content here.

##### Example:
```
[bucket_project_info true=""][/bucket_project_info]
```

Project
---

![Project shortcode](http://i.imgur.com/0S82mna.png)

1. **Project Categories** select project categories by clicking checkbox.
2. **Total Project:** add no. of projects want to display.

##### Example:
```
[bucket_project max_project="2"]
```

Slider
---

![Slider Shortcode](http://i.imgur.com/Ly7nwfG.png)

1. **Upload Images:** add as many images as you want for slider.
2. **Speed:** add duration of animation between slides.
3. **Autoplay:** click this box to enable/disable autoplay of slider.

##### Example:
```
[bucket_slider images="321,317,263,261,277" speed="5000"]
```

Team Carousel
---

![Team Carousel Shortcode](http://i.imgur.com/w0JraP1.png)

1. **Speed:** add duration of animation between slides.
2. **Autoplay:** click this box to enable/disable autoplay of slider.
3. Click to add team item on carousel.

##### Example:
```
[bucket_team autoplay="true"][/bucket_team]
```

Testimonial Carousel
---

![Testimonial carousel Shortcode](http://i.imgur.com/ahvECeH.png)

1. **Speed:** add duration of animation between slides.
2. **Autoplay:** click this box to enable/disable autoplay of slider.
3. Click to add team item on carousel.

##### Example:
```
[bucket_testimonials autoplay="true"][/bucket_testimonials]
```