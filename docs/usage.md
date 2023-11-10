# Usage Guide

## Get Started

Thanks for using our theme!

To set up the theme exactly like our demo stores, you may need to install the our free app **[PapaThemes Widgets](https://www.bigcommerce.com/apps/papathemes-widgets/)**. This app provides additional widgets to build the content in Page Builder visually without coding skill. 

For displaying your Instagram photos on your website, you can use our free tool **[PapaThemes Instagram](https://instagram.papathemes.com/)**. We will guide you step by step later in this manual.

### Customizing Typography, Fonts and Colors

Customizing Typography, Fonts and Colors, Buttons in **Page Builder** > **Theme Styles** > **General**. There are dozens of options to help you customize your website beautifully and uniquely.

### Customizing Checkout Page's Typography and Colors

Customizing the checkout page's typography and colors in **Page Builder** > **Theme Styles** > **Optimized Checkout**

### Installing PapaThemes Widgets App

Find and install **[PapaThemes Widgets](https://www.bigcommerce.com/apps/papathemes-widgets/)** app from [BigCommerce Apps Marketplace](https://www.bigcommerce.com/apps/).

After installed, go to your admin page, on the left sidebar, click **Apps** >** My Apps**, click **Launch** button of PapaThemes Widgets app to open the app:

![launch-papathemes-widgets-app](img/launch-papathemes-widgets-app.jpg)

Then click the Install buttons in turn to install all available widgets:

![install-papathemes-widgets](img/install-papathemes-widgets.jpg)

Go to **Storefront** > **My Themes** > click **Customize** in dropdown menu of Antique theme to open Page Builder. Select any theme style to start:

![click-theme-customize](img/click-theme-customize.jpg)

Verify the widgets installed successfully if they appear in Page Builder:

![custom-widgets-appear](img/custom-widgets-appear.jpg)

## Setting Up Furniture Style Home Page

To start customizing the theme, login to your admin panel, go to **Storefront** > **My Themes**, click **Customize** button next to theme thumbnail.

### Header

![Header](img/header.jpg)


To configure the header, click on **Theme Styles** > **Header** section, here you can config the header colors, store logo position and size.

Click on **background color** to change header color.

![header-backgroundcolor](img/header-bgcolor.jpg)

The theme allow user to change **Logo** > **Position**  to `left`, `right` or `center`.

**User Navigation** allows to change colors of text, text hover and dropdown have background, border, cart counter. To display **Phone** and **Currency** in header select `Show`

**Top Bar** section allows to change color of this top bar.

![Top Bar](img/top-bar.jpg)

- **Background** :  You can change the background color of the top bar to your preference.

- **Text** : You can modify the text color of the top bar according to your liking.

- **Text hover** :  You have the ability to change the color of the text when hovering over it in the top bar.

- **Icon** :  You can customize the color of the icons displayed in the top bar.
#### Quick search

**Quick Search** allows user to change the colors of the search form.

To configure the **Quick Search**, click on **Theme Styles** > **Header**. In **Quick Search** section you can change text colors, hover, border, and background of the search field.

To change popular search keywords, type your text in **popular search keywords** field as picture below.

![header-quick-search](img/quick-search.jpg)
#### Main Navigation

**Main Navigation** allows to customize this navigation bar like changing the menu type to column, dropdown menu or mega menu; changing colors of the top menu as well as the sub-menus. There is an option "**Hide webpage links**" that allows to hide the static web page links on the main navigation.

To configure the Main navigation, click on **Theme Styles** > **Header**. In **Main navigation** section you can change:

- **Root menu item color**: text color of root menu item.

- **+ Hover**: text color on hover on the root menu item.

- **+ Background**: background color of sub menu block.

- **+ Background (Mobile)**: background color of menu on mobile device.

- **Sub menu item color**: text color of the submenu item.

- **+ Hover**: text color on hover on the submenu item.

- **+ Background**: background color of the submenu item.

- **+ Background hover**: background color on hover on the submenu item.

- **+ Border**: border-color of mega menu popup.

![main-navigation](img/main-navigation.jpg)

To config style of main navigation, click on **Theme Styles** > **Header**. In **Main navigation** select **Menu style**. The theme offer 3 option as below:

- `Mega menu`: show submenu under Mega menu style. **Mega menu** allow user insert banner and product into it

![mega-menu](img/mega-menu.jpg)

- `Dropdown`: show sub-menu item as dropdown style.

![dropdown-menu](img/dropdown-menu.jpg)

- `Column`: show sub-menu item as column style.

![column-menu](img/column-menu.jpg)

You can also hide or **Show web page links** and **Show widgets in the mega menu**.
#### Hide webpage links

To hide Webpage links such as **Contact us**, **About Us**, **Shipping and return** from header, in **Themes style** > **Header** Find **Hide Webpage links** option checked to hide all the links except **Categories** link.

If you only want to hide some specific links not all the link you can do following step:

- `+ Begining` field: input the order link you want to show.
- `+ Limit` field: input number web link you want to show after begining field.

For example: if you only want show **About Us** and **Theme Features**:
- Begining field: 1;
- limit field:  2;

Note: the order will only count non-categories link.

Before
![web-links-order](img/web-links-order.jpg)

Affer:
![hidden-web-links](img/hidden-web-links.jpg)

### Top Banner

Go back to **Storefront** > **My Themes** > click **Customize** button beside the theme thumbnail. You can see the top banner appears above the header. To change the colors of the top banner, go to **Theme Styles** > **General** > **Top banners** section. Here you can change the text color and the background color.
### Main carousel

![main-carousel-manager](img/main-carousel-manager.jpg)

Upload the carousel images in **Storefront** > **Home Page Carousel**.

Go back to **Page Builder**, in **Theme Styles** > **Home Page**, make sure **Carousel** > **Show carousel** is selected, unchecked **Show top col**, **Show left col** and **Show right col** . You can change the carousel styles and colors here.

#### Left column banner in homepage carousel

![Main-carousel-left-banner](img/left-col-banner.jpg)

To display left banner in Main carousel.

Click on **Theme Styles** > **Home Page** > **Carousel** find show **left column** and enable it to open widget region.

Drag & drop layout widget from page builder to corresponding position in **left column**. Change column to 1. Set **margin left** and **margin right** = `0`. Select column 1 and change **padding left** and **padding right** = `0`.

Drag & drop **Flex Banners | PapaThemes Chiara** widget to layout. Delete all banner **except banner 1**. In Banner click on **Image** and upload your image. Change image **width** = `362px` and **height** = `440px`. Unchecked **Hover animation**.

In **General** > **Padding** = `0` for all device. Uncheck **Displpay banners in container div**

To remove border please create custom script as follow.

Go to **Storefront** > **Script Manager**, click **Create a Script**, choose:

- **Placement** = `Footer`
- **Location** = `Storefront pages`
- **Script type** = `Script`
 
Enter the script below to Scripts contents:
 
```
<script>
(function() {
var style = document.createElement('style');
style.innerHTML = '.heroCarousel-left-col{border:none}';
document.head.appendChild(style);
})();
</script>
```

#### Right column banner in homepage carousel
![Main-carousel-right-banner](img/right-banner-main-carousel.jpg)

To display right banner in Main carousel.

Click on **Theme Styles** > **Home Page** > **Carousel** find show **right column** and enable it to open widget region.
 
Drag & drop layout widget from page builder to corresponding position in **right column**. Change column to 1. Set **margin left** and **margin right** = `0`. Select **column 1** and change **padding left**, **padding right** = `0`.

Drag & drop **Flex Banners | PapaThemes Chiara** widget to layout. Delete all banner **except banner 1**. In Banner click on **Image** and upload your image. Change image **width** = `362px` and **height** = `204px`. In General section, set all padding value `0` for all device.

Duplicate **Flex Banners | PapaThemes Chiara** widget. Select second banner change your **image** and **overlay image**.
#### Stretch banner in homepage carousel
![Carousel Stretch](img/carousel-stretch.jpg)

To display banner in Main carousel.

Click on **Theme Styles** > **Home Page** > **Carousel** > **Style** = `Stretched`. Unchecked **Show top col**, **Show left col** and **Show right col**.
### Slider Sale

![slider-sale](img/slider_menu.jpg)

Drag & drop **HTML** widget to the correspoding position.
 
Select **Column 1**, set Padding = `0 0 0 0`, 

Seletct **Layout** set **Layout Background**  to a certain color that you want.

Paste the given code below to the HTML editor, then click Save HTML button.

```html
<div class="list-ctgry">
  <a href="#" class="item-ctgry">
      GAME DAY FURNITURE SALE
  </a>
  <a href="#" class="item-ctgry">
    THE ENTRYWAY SALE
    </a>
  <a href="#" class="item-ctgry">
    THE WHITE SALE
  </a>
  <a href="#" class="item-ctgry">
    OUTDOOR WARM-UP SALE
  </a>
    <a href="#" class="item-ctgry">
        GAME DAY FURNITURE SALE
    </a>
  <a href="#" class="item-ctgry">
    THE ENTRYWAY SALE
    </a>
  <a href="#" class="item-ctgry">
    THE WHITE SALE
  </a>
  <a href="#" class="item-ctgry">
    OUTDOOR WARM-UP SALE
  </a>
  <a href="#" class="item-ctgry">
      GAME DAY FURNITURE SALE
  </a>
  <a href="#" class="item-ctgry">
    THE ENTRYWAY SALE
  </a>
  <a href="#" class="item-ctgry">
    THE WHITE SALE
  </a>
  <a href="#" class="item-ctgry">
    OUTDOOR WARM-UP SALE
  </a>
</div>
```

To insert the link, simply paste your desired link within the 

`
<a href="YOUR LINK HERE" class="item-ctgry"> YOUR TEXT HERE </a>
`

### Featured Categories

![featured](img/featured.jpg)

Drag & drop layout widget to region `Home Below Carousel` which is below homepage carousel, as picture below:

![postion featured](img/featured-home-carousel.png)

Drag and drop **Layout** widget to the corresponding position, change **Column** = `1`. Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | PapaThemes Beautify**. Typing your text (example "**Featured Categories** - Easy living room updates with free ship over $49"), select custom in **Text style** field, set **Font size** and **Font size (Mobile)** = `18px`, **Text color** = `#000000`, set **Padding** = `0 0 0 0`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget into **Column 1** below **Section Heading** widget to layout. Delete all banner **except banner 1**. 

Upload your image, set **Image width** = `375px`, **Image height** = `375px`. If you want to show different image on mobile please enable **Show different image on mobile** upload your image in **Image (Mobile)** field.

In **Content** set **Content Padding** = `0 0 40 0`, **Content padding (Tablet)**  = `0 0 25 0`, **Content padding (Mobile)** = `0 0 22 0`.

Tick active **Action button** . Choose **Style** = `Custom`, **Radius** = `0px`, **Color** = `#FFFFFF`, **Color hover** = `#06455E`, **Text color** = `#3F3F3F`, **Text color hover** = `#FFFFFF`.

In **General**, choose **Width** = `%`, set value **Desktop** = `25%`, **Tablet** = `33,33%`, **Mobile** = `50%`.

Set **Padding** value **Desktop** = ` 25 15 25 15`, **Tablet** and **Mobile** = `15 10 15 10`.

Duplicate **banner 1** to quantity that you want and update your image and content for each banner.

In **Settings** :

Choose **General**, **Style for theme** = `Beautify Furniture`, unchecked **Display banners in container div**

Choose **Carousel**, show **Enable carousel**, in **Carousel settings** panel set value **Items per slide** = `4`, **Items per slide (Tablet)** = `4`, **Items per slide (Mobile)** = `2`, unchecked **Show arrows**.
### Category Banner

Desktop : 

![category banner](img/category-banner.jpg)

Mobile : 

![category banner mobile](img/category-banner-mobile.jpg)

Drag and drop **Layout** widget to the corresponding position, change **Column** = `1`. Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | Papathemes Beautify**. Typing your text(example "Help yourself to a stylish dining room"), select custom in **Text style** field, **Text style** = `Custom`, **Font weight** = `Semi Bold`, **Font size** and **Font size(Mobile)** = `18px`. Set value **Padding** = `46 0 25 0`, **Padding(Mobile)** = `16 0 18 0`.

Drag & drop **Layout** widget , **Columns** = `2`. **Column layout** with a ratio of `4/12`.

**Column 1** :

Drag & drop **Spacer** = `25px`.

Drag & drop **Text** :

**Text style** = `Custom`, **Font weight** = `Normal`, **Font size** = `15px`, set value **Padding** = `0 25 22 25`.

Drag & drop **Button** : 

In **Button**, set **Padding** = `5 5 5 5`. 

In **Text**, set **Font size** = `12px`, **Text color** = `#000000` and **Text color(hover)** = `#ffffff`.

Drag & drop **Spacer** = `25px`.

**Column 2** :

Drag & drop **Flex Banners | Papathemes Beautify** to the layout delete all the items except the first one then change to your image change **width** = `1000px` and **height** = `368px`. In **Settings** unchecked **Display banners in container div**

The rest remains the same, only the position is changed.

### Featured products

![featured-products](img/feature-product.jpg)

You can set featured products in **Products**, click the **star** icon on the same row to set the product as featured.

Go back to **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** field has **Featured Products** selected. In **Featured products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

### New Product

![new-products](img/new-product.jpg)

You can configure new products section settings in **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** field has **New Products** selected. In **New products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

### Bestselling products

![bestselling-products](img/best-selling-product.jpg)

Bestselling products only display when your store has some order.

You can configure bestselling products section settings in **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** field has **Popular Products** selected. In **Best-sellers products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

### Double Banner

Desktop :

![Double Banner](img/double_banner.jpg)

Mobile : 

![Double Banner Mobile](img/double_banner--mobile.jpg)

Drag and drop **Layout** widget to the corresponding position, change **Column** = `1`. Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget into **Column 1**. Delete all other banners except the first one.

Upload your image, set **Image width** = `737px`, **Image height** = `147px`. If you want to show different image on mobile please enable **Show different image on mobile** upload your image in **Image (Mobile)** field.

Set **Padding** value **Desktop** = `0 16 0 0`, **Tablet** and **Mobile** = `0 0 20 0`.

In **Settings** of **Flex Banners | PapaThemes Beautify** > **General**, choose **Width** = `%`, set value **Desktop** = `50%`, **Tablet** and **Mobile** = `100%`, unchecked **Diplay banners in container div**.

Duplicate to 2 banners and upload images according to each banner.

### Brand

![brand](img/brand.jpg)

Drag and drop **Layout** widget to the corresponding position, change **Column** = `1`. Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | PapaThemes Beautify** widget into **Column 1** :

Typing your text (example "We Carry Top Brands"), select custom in **Text style** field, **Text style** = `Custom`, **Font weight** = `Semi Bold`, **Font size** and **Font size(Mobile)** = `18px`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget to layout. Delete all banner **except banner 1**.

Upload your image, set **Image width** = `278px`, **Image height** = `96px`. If you want to show different image on mobile please enable **Show different image on mobile** upload your image in **Image (Mobile)** field.

In **general**, choose **Width** = `%`, set **Value(Desktop)** = `20%`, **Value (Tablet)** = `33,333333%`, **Value (Mobile)** = `50%`. Set **Padding** for **Desktop** = `20 12 20 12`, **Tablet** and **Mobile** = `15 10 15 10`. Uncheck **Display banners in container div**.

On **Flex Banners | PapaThemes Beautify** choose **Settings**

In **carousel**, show **enable carousel** and click on setting **Items per slide** = `5`, **Items per slide (Tablet)** = `3` and **Items per slide (Mobile)** = `2`. Enable **show dots**.

Duplicate **banner 1** to quantity that you want and update your image for each banner.

### Product by category

With **Left banner**:

Desktop : 

![Product by category](img/product-by-category.jpg)

Drag & drop layout widget to region `Pbcst 0` which is below home below section3, as picture below:

![Position widget product by category](img/position-product-by-category.jpg)

With out **Left banner**:

![Product by category](img/product-by-category-2.jpg)

Go to **Theme Styles** > **Home Page**, in the **Sections** field select **Product by category**.

Drag & drop the **Flex Banners | PapaThemes Beautify** widget to the corresponding position. Delete all other banners except the first one.

Upload your image in **Image** field. Set **Image Width** = `326px` and **Image Height** =`508px`.

If you want to show different image on mobile please enable **show different image on mobile** upload your image in **Image (Mobile)** field. Set **Image Width (Mobile)** = `401px` and **Image Height (Mobile)** = `295px`.

In **Content**, hide **Heading text** if your banner already has text.

In **General** > **Padding** panel, set `0` for all values then set value `24` for **bottom (Mobile)**.

Select the **Column 1** set padding = `0 0 0 0`.

To change **Border color of the title**:

In **Theme Styles** > **General** > **Link Colors** change color you want.

### Slider Furnisima

![Slider Furnisima](img/slider-category.jpg)

Drag & drop layout widget to region `Pbcst Below 0` which is below Pbcst4, as picture below:

![Product by category below](img/pbcst-below.jpg)

Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget to layout. Delete all banner **except banner 1**.

Upload your image, set **Image width** = `432px`, **Image height** = `58px`. If you want to show different image on mobile please enable **Show different image on mobile** upload your image in **Image (Mobile)** field.

In **Content** set value **padding** = `0 0 0 0`.

Turn on **Heading text** : 

**Text style** = `Custom`, **font weight** = `Semi Bold(Demi Bold)`, **font size** and **font size (Mobile)** = `13px`, **text color** = `#000000`,
**text color hover** = `#003366`, **text color (Mobile)** = `#000000` and **text color hover(Mobile)** = `#003366`

Turn on **Description text** : 

**Description style** = `Custom`, **font weight** = `Normal`, **font size** and **font size (Mobile)** = `11px`, **Text color**, **Text color hover**,
**Text color(Mobile)** and **Text color hover (Mobile)** = `#000000`.

In **General** :

Choose **Width** = `%`, set **Value (Desktop)** = `25%`, **Value (Tablet)** = `33,3333%`, **Value (Mobile)** = `50%`.

Set **Padding** for **Desktop** and **Tablet** = `10 10 10 10`, **Mobile** = `10 5 10 5`.

Duplicate **banner 1** to quantity and change the content you want.

On **Flex Banners | PapaThemes Beautify** choose **Settings** : 

**Style for theme** = `Kansha Sport`, unchecked **Display banners in container div**.

Choose **Carousel** turn on **Enable Carousel**. In carousel setting, **Items per slide** and **Items per slide (Tablet)** = `4`, **Items per slider (Mobile)** = `2`, unchecked **Show arrows**.

### Recent blog posts

![edit-recent-blog](img/edit-recent-blog.jpg)

You can add blog posts in Storefront > Blog. Click the **+** button to add a new blog post. Make sure **Blog Visibility** is `on`.

To display the recent blog posts on the home page, go to Page Builder. In Theme Styles > Home Page, make sure one of Sections has **Recent Blog** selected. Scroll down the Recent Blog section, you can configure **Heading**, **Number of posts** to display.

### Live Help

![live help](img/live_help.jpg)

Drag & drop **Layout** widget to the corresponding position, change **Column** = `1`, **Padding** = `0 0 0 0`.

Drag & drop **Divider**, select **Line color** = `#DEDEDE`, **Line thickness** = `3px`.

Drag & drop **Layout** widget below **Divider** widget, change **Column** = `2`, **Padding** = `0 0 0 0`, Column layout with a ratio of `9/12`.

**Column 1** :

Drag & drop **Text**, set **Text style** = `Custom`, **Font weight** = `Medium`, **Font size** = `14px`, **Text color** = `#333333`

**Column 2** : 

Drag & drop **Button**, choose **Button** set value **Padding** = `7 21 7 21`, choose **Text** set **Font size** = `14px`.

Choose **Style** set **Button color** = `#06455E`, **Button color (hover)** = `#003366`, **Border color** and  **Border color (hover)** = `No Color`, **Border thickness** and **Border radius** = `0px`

### Contact

![Contact](img/contact.jpg)

Drag & drop **Layout** widget below **Live Help**, change **Column** = `1`, **Padding** = `0 0 0 0`.

Drag & drop **Callout Icons | Papathemes Beautify** widget to layout. Delete all callout **except callout 1**.

**Style** = `Large`, choose **Width** = `%`, set **Value (Desktop)** = `25%`, **Value (Tablet)** = `50%`, **Value (Mobile)** = `100%`. Set all padding value `30 16 30 16` for all device.

Select **Icon** = `Choose Image`, **Text style** = `Custom`, **Font weight** = `Semi Bold(Demi Bold)`, **Font size** and **Font size (Mobile)** = `15px`, **Text color** and **Text color hover** = `#000000`.

Tick active **Show second text**, select **Second text style** = `Custom`, **Font size** and **Font size (Mobile)** = `13px`, **Text color** and **Text color hover** = `#000000`. Unchecked **Display icons in container div**.

Duplicate **Callout 1** to 4 callout.

### Instagram photos

![edit-instagram](img/edit-instagram.png)

To display your Instagram photos, open <https://instagram.papathemes.com/> Follow the instruction on this page to [Connect your Facebook Page with your Instagram account](https://www.facebook.com/business/help/898752960195806). Then click **Login With Facebook** button and follow the further steps to authorize access permission. Click **Show Embedding Code** button to generate the code embedding to your web store. Choose **Preset** = `Carousel` and select **LazyLoad**.

Copy all the code appear in Step 1 & Step 2. For example:

```html
<script>!function(){var a=document.createElement("script");a.defer=!0,a.src="https://papathemes.s3.amazonaws.com/instagramapp/assets/js/embed-1.0.1.js",a.onload=function(){PapathemesInstagramApp.init({account_id:"****************",element_id:"papainstagram-render",limit:"20",preset:"grid",lazyload:"false"})},document.body.appendChild(a)}();</script>

<div id="papainstagram-render"></div>
```

Go back to your store Page Builder. Drag & drop the HTML widget to the corresponding position. Paste the generated code above to the HTML editor, and click **Save HTML** button. Your Instagram photos should display like our demo store.

Please note that the app only updates your latest uploaded photos every 6 hours.

To create the title, drag & drop the **Section Heading** widget to above the Instagram photos. Set **Padding** = `0 0 28 0` and **Padding (Mobile)** = `18 0 18 0`.

### Newsletter

![Newsletter](img/newsletter.jpg)

To enable newsletter form, go to **Marketing** > **Email Marketing**, make sure **Allow Newsletter Subscriptions** is checked. Optionally select **Show Newsletter Summary** and enter the summary text as you want.

Go to Page Builder, in **Theme Styles > Footer > Newsletter** section, select **Style** = `Default`. Select **Show store logo** and **Show social icons** = `In newsletter`. Make sure **Show newsletter form** is selected. You can change the **Heading, background color, background image, button** and **text colors**.

### Footer

![footer](img/footer.jpg)

In **Page Builder** > **Theme Styles** > **Footer**, you can configure the newsletter form appearance in **Newsletter** section, configure the footer link colors in **Main Footer** section, displaying store logo, contact info, store address,... **Show pages** allows to limit number of web page links to display. **Show categories** allows to limit number of category links to display. Similarly for **Show brands** option.

**Payment Icons** allows to select which payment icons to display.

**Copyright** allows to configure the copyright text.

### Display custom footer links

In **Page builder** > **Custom Widget** find **Footer links | PapaThemes Beautify** widget then drag and drop the widget to corresponding position in Footer.

Select the **Column 1** and change **padding** to `0`

In **design** you can type your link content and click on the **insert/edit link** button as picture below:

![footer-links](img/footer-link-widget.jpg)

In the popup window, copy your web link to `URL`. On the **Open links..** field you can select how your link could be open in **New Window** or **Current Window**

![Insert-links](img/insert-links.jpg)

## Customizing Products Display

### Product Card

![configure-product-card](img/configure-product-card.jpg)

Configuring product cards in **Page Builder** > **Theme Styles** > **Products** > **Product cards**.

- **Alignment**: Specifying content alignment `left` or `center`.
- **Product title color**: Specifying the product name's color.
- + **Hover**: Specifying color when hover or focus.
- **Button text color**: Specifying the button text color.
- + **Background**: Specifying the button background color.
- + **Border**: Specifying the button border color.
- **Show second image on hover**: Displaying the second image when hover the product card.
- **Show border**: toggle displaying the product card border.
- **Show swatch/rectangle options**: Allows to display with swatch/rectangle type product option on every product card. It's helpful to display different product variants like colors or sizes.
- **Swatch sizes**: Specifying the swatch color/image size.
- **Badge position**: also to configure the sale badge position to `Top Left` or `Below image`.

### Displaying product price ranges

By default product price ranges is enabled. To turn off, Go to **Page Builder** > **Theme Styles** > **Products** > uncheck **Price ranges** checkbox.

**Show retail price**: Toggle displaying the product retail prices.


### Hiding prices for non logged in customers

To turn on this feature, go to **Page Builder** > **Theme Styles** > **Products** > tick **Restrict Purchase to Login** checkbox.

![hide-prices](img/hide-prices.jpg)

### Redirecting to cart page after product added to cart

By default the cart popup is displayed, if you want to take customer to the cart page instead, go to **Page Builder** > **Theme Styles** > **Products** > tick **Redirect to cart page after add to cart** checkbox.

### Showing/Hiding Quick-View button

By default quick-view buttons appear on all product cards. To hide it, go to **Page Builder** > **Theme Styles** > **Products** > un-tick **Show Quickview** checkbox.

### Showing/Hiding the quantity box on PDP

By default the quantity box shows up, to hide it, go to **Page Builder** > **Theme Styles** > **Products** > un-tick **Show quantity selection on product pages** checkbox.

### Customizing the popup displayed after product added to cart

In **Page Builder** > **Theme Styles** > **Products** > **Popup after added to cart**:

- `Default`: Displaying the large popup.
- `Mini`: Displaying a smaller popup that has auto close.
- `Cart Preview`: Displaying the whole shopping cart popup on the right side.
- `Hide`: Not show any popup.

Mini added to cart popup:

![mini-add-to-cart-popup](img/mini-add-to-cart-popup.jpg)

### Displaying Recently Viewed Products

Recently viewed products only display for logged-in customers.

To enable it, go to **Page Builder** > **Theme Styles** > **Products** > **Show recently viewed** select number of products to display.


### Customizing Price Labels

You can customize sale price label, before sale price label, retail price label or regular price label in 
**Page Builder** > **Theme Styles** > **Products** > **Price Labels**

![configure-price-labels](img/configure-price-labels.jpg)

### Displaying product weight, dimensions on PDP

Go to **Page Builder** > **Theme Styles** > **Products** > **Product Page**.

- Tick **Show product weight** checkbox.
- Tick **Show product dimensions** checkbox.

### Display sale badge / in-stock badge on PDP

Go to **Page Builder** > **Theme Styles** > **Products** > **Product Page**.

- Tick **Show sale badge** checkbox.
- Tick **Show in-stock badge** checkbox.

### Displaying Image gallery 

#### Image Gallery Position

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, In **Image gallery position** , select `Left` or `Right` to change Image gallery position .

- `Right`

![pdp-right](img/pdp-right.jpg)



#### Displaying sub-image as a slider

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, **Enable thumbnail carousel** section, you can change display thumbnail images to slider or grid.

- `1 row`: Sub-images are displayed in the slider on 1 row.

- `2 rows`: Sub-images are displayed in the slider on 2 row.

- `Hide`: All sub-images are displayed as grid.

![thumbnail-2](img/thumbnail-2.jpg)


#### Displaying product image thumbnails vertically

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, checked **Show image thumbnails vertically** to display product thumbnails vertically, otherwise it's displayed horizontally.

Checked **Show image thumbnails vertically**:

![thumbnails-vertically](img/thumbnail-vertical.jpg)

### Displaying product bulk pricing inline in table

Instead of displaying bulk pricing in a popup modal, you can display it inline by going to **Page Builder** > **Theme Styles** > **Products** > **Product Page**, tick **Show bulk price as table**.

![bulk-pricing-table](img/bulk-pricing-table.jpg)

### Displaying sticky Add to Cart button on PDP on mobile

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, tick **
Show sticky Add to Cart on mobile**.

![Show sticky Add to Cart on mobile](img/sticky-add-to-cart.jpg)

### Displaying product custom fields in a separated tab

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- Tick **Show custom fields in tab** checkbox.
- Enter the tab title in the next **Tab title** box.

![product-custom-fields-tab](img/product-custom-fields-tab.jpg)

### Custom tabs

![Custom-tab-sample](img\custom-tab-sample.jpg)

To add the custom tabs and product pages, edit your product description, click on HTML button to open HTML Source Editor:

![Custom-tab](img\custom-tab.jpg)

Use the editor in the [link](https://bc-supermarket-docs.papathemes.com/customization/product-page#custom-tabs) to generate HTML for your custom tabs. Click Export HTML button, copy & paste the generated HTML at the end of HTML Source Editor.

### Displaying Delivery & Returns tab

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- Tick **Show Delivery & Returns tab** checkbox.
- Enter the tab title in the next **Tab title** box.

You can add specific content or global content using BC widgets:

![add-widgets-to-delivery-returns-tab](img/add-widgets-to-delivery-returns-tab.jpg)


### Numbers of products, reviews, thumbnails

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- **Number of Product Reviews**: Specifying number of product reviews displayed.
- **Number of Related Products**: Specifying number of related products displayed.
- **Number of Customers Also Viewed Products**: Specifying number of customer also viewed products displayed.
- **Number of visible thumbnails**: Specifying number of images displayed in the product thumbnails slider.


### Displaying Swatch Options in the dropdown select box

In **Page Builder** > **Theme Styles** > **Products** > **Swatch display type**:

- Default (Square): Displaying the regular swatches by default.
- Dropdown: Displaying swatches in the dropdown select box.
- Dropdown + Square: Displaying swatches in the dropdown select box in addition to regular swatches.

![swatch-dropdown](img/swatch-dropdown.png)


### Displaying Frequently Bought Together Products

![frequently-bought-together](img/frequently-bought-together.jpg)

Enabling this feature in **Page Builder** > **Theme Styles** > **Products** > **Frequently Bought Together**, Select **Position** to display it.

- **Load products from**: Specifing products to display here.
  - `Custom fields __alsobought`: Specifying the relevant products in product custom fields with name `__alsobought` and value is the relevant product ID. For example:
  ![edit-product-bought-together](img/edit-product-bought-together.jpg)
  - `Related products`: Pulling from the related products.
  - `Similar by biews`: Pulling from customer also viewed products.
- **Auto select all items**: Auto select or unselect all frequently bought together products.
- **Thumbnail size**: Specifying the thumbnail image size.
### Configuring swatch dimension

In **Page Builder** > **Theme Styles** > **Products** > **Swatch display type** > Set **Swatch size**.


### Sale badge, Condition badge and custom text badges

![product-badges](img/product-badges.jpg)

Displaying the sale badge in **Page Builder** > **Theme Styles** > **Products** > **Product sale badges**, tick **Show sale badges**.

- **Label**: Specifying the badge text.
- **Text color**: Specifying the badge text color.
- **Background color**: Specifying the badge background color

Displaying the condition badge in **Custom badges**, tick **Enable custom badge from '__badge' custom field**. Edit product, add custom field with name `__badge` and value is the badge text.

- **Text color**: Specifying the text color of the custom badge.
- **Background color**: Specifying the background color of the custom badge.

### Configuring image sizes


In **Page Builder** > **Theme Styles** > **Products** > **Image Sizes**:

- Main product images: Specifying the main product image size displayed on PDP.
- Thumbnail image: Specifying the product thumbnail size.
- Zoomed image: Specifying the zoomed image size.
- Image in gallery view: Specifying product card image size.

### Shipping countdown

![shipping-countdown](img\Shipping-countdown.jpg)

To enable shipping countdown, **Theme styles** > **Product page**  find **shipping countdown** field and input your cut off time. Find and copied your timezone from wikipedia `https://en.wikipedia.org/wiki/List_of_tz_database_time_zones` to **timezone** field.

Note: The time before cut off the message will show **shipping today** after cut off the message will show **shipping tomorrow**

### Flash sales

![Flash-sales](img\flash-sales.jpg)

To create flash sales bar for each product, in **product** select the product that you want to add flash sale bar. 

Find customer fields, click on add **Add Custom Field**. Copy `__countdown_label` and paste into **Custom Field Name**. In **Custom Field Value**, type your content following format: `<your banner name>|<end in>` (example: FLASH SALES|ENDS IN). 

Create another custom field, Copy `__countdown_date` and paste into **Custom Field Name**. In **Custom Field Value**, enter your cut off time following the format: `<yyyy>-<mm>-<dd> <hh>:<mm>:<ss><timezone>` (example: 2023-03-15 17:00:00-7).

Note:

- `<yyyy>-<mm>-<dd>` is optional. If the date is not entered, the banner will repeat automatically right after pass cut off time.
  
- `<hh>:<mm>:<ss>` is 24 hour format.
  
- `<timezone>` only input `+ or -` and `number` example: `+7`. if timezone are not entered, the countdown time will be different in different countries.
### Brand logo in product detail

![brand logo in product detail](img/brand-logo.jpg)

To display **Brand logo** in product detail, in **Page Builder** > **Products** > **Product Page** find and check **Show brand image** option.


### Ask question

In **Page Builder** > **Theme Styles** > **Products** > **Product Page** find **Ask question (contact page URL)** and enter `/contact-us/` to display **Ask Questions?**.

![ask question](img/ask-question.jpg)


### Nutrients & Directions

![Nutrients & Directions result](img/nutrients-directions-link.jpg)

To create additional information link:

In **Storefront** > **Web Pages**, click on the **Create a Web Page** button to create new webpage.

In **Web Page Details**, enter your page name in **Page Name** field, **Page URL** will be automatically generated. In **Page content** field enter your content.

Uncheck **Navigation Menu** options.

In **Advanced Options** set **Sort Order** = `2`.

To display the additional information link in the product detail page:

In **Products**, select the product you want to display the link. Find **Custom Fields**, created new custom field. Set **Custom Fields Name** = `__guide_popup` and **Custom Fields Value** = `<your page name>|<Page URL>` (example: `Nutrients & Directions|/nutrients-directions/`) then save.

### Video image product detail page

In **Page Builder** > **Theme Styles** > **Products** > **Product Page** find **Show videos** select `tab` or `image gallery` to change display video position.

Videos displayed in **tab** options:

![video image product detail tab option](img/video-image-PDP-tab.png)

Videos displayed in **image gallery** option:

![video image product detail image gallery option](img/video-image-PDP-image-gallery.png)

## Customizing Category Pages

Configuring the category pages in **Page Builder** > **Theme Styles** > **Products** > **Category Page**.

### Category Layout Type

Theme supports displaying category Page layout in `Full width` mode or `Left sidebar` mode. In **Layout**, select the particular display mode for default display.

- **Layout** = `Full width`

![full-width](img/category-fullwidth.jpg)

- **Layout** = `Left sidebar`
 
![left-sidebar](img/category-leftsidebar.jpg)

### Products Display Type

Theme supports displaying products in grid mode (2, 3, 4 or 6 products per row), in list mode or bulk order mode. In **Products display type**, select the particular display mode for default display.

- **Display type** on the right allow your customers to change product category display by themselves.
![products-display-type-by-customer](img/products-display-type-by-customer.jpg)

**Grid 6 columns:**

![products-display-type-grid6](img/products-display-type-grid6.jpg)

**List mode:**

![products-display-type-list](img/products-display-type-list.jpg)

### Display Bulk Order layout

To display this bulk order layout, select **Products display type** = `Bulk order`.

![products-display-type-bulk-order](img/products-display-type-bulk-order.jpg)

### Displaying Shop by Brand

- **Shop by Brand**: Specifying number of popular brands to display.

![popular-brands-sidebar](img/popular-brands-bar.jpg)

### Displaying Price Slider

- **Shop by Price**:
  - `Slider`: Displaying the price slider.
  - `List`: Displaying price list.
  - `Hide`.

![shop-by-price-slider](img/shop-by-price-slider.jpg)

### Infinite Products Loading

This feature allows you to choose the method of loading more products in the current catalog.

![infinite-product-loading](img/infinite-product-loading.jpg)

**Infinite Products Loading**:

  - `On scroll`: Products will automatic loadout when scrolling down.

  - `Load more button`: Click on the **Load more button** to continue loading more products.

  - `Off`: Show **page numbers** and **arrow** button as original. Click on button to see more products.

### Display contextual search

This feature allows searching products within the current category and the current selected filter.

![contextual-search](img/contextual-search.jpg)

Select **Show quick search in category** = `Show` to enable it.

- **+ Show results in descendent categories**: if selected, it also displays results in the descendent categories.

### Display subcategory image thumbnails

This feature allow displaying subcategory thumbnails before products.

Select **Show subcategory thumbnails** to enable it.

![subcategory-thumbnails](img/subcategory-thumbnails.jpg)

### Common Settings

- **Number of products per page**: Specifying number of products to display per page.
- **Show category image**: Displaying the category image or not.
- **Show category description on AMP page**: Displaying category description on AMP category page or not. If the category content contains images, the AMP page could be invalid. It's recommended to turn off this option.

## Customizing Brand Page & Search Page

Configuring the brand page in **Page Builder** > **Theme Styles** > **Products** > **Brand Page**.

- **Number of brands per page**: Specifying number of brands to display per page.
- **Number of products per page**: Specifying number of products to display per page.
- **Brand image in gallery view**: Specifying the brand card image size.
- **Brand image in brand page**: Specifying the large image size displayed on the brand page.

Configuring the search results page in **Page Builder** > **Theme Styles** > **Products** > **Search results**.

- **Number of products per page**: Specifying number of products to display on the search results page.

### Displaying brand quick-view introduction

![brand-quick-view](img/brand-quick-view.jpg)

In **Marketing** > **Marketing Banner**, click **Create a Banner** button. 

- Enter the brand introduction content to **Banner Content**.
- Select **Show on Page** = `For a Specific Brand` and select the corresponding brand.
- Select **Location** = `Bottom of Page`.
- Then click **Save** button to finish.