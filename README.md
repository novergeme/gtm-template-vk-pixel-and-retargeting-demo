# Welcome!

This is an instruction for installing and configuring the VK Pixel & Retarget Demo template for Google Tag Manager.


## 1. Install the VK Pixel & Retarget Demo tag

You can install the tag from the GTM Template [Gallery](https://tagmanager.google.com/gallery/#/?page=1) (use the search and find the template by the name "VK Pixel&Retarget DEMO", [instructions](https://support.google.com/tagmanager/answer/9454109?hl=ru) for using the Template Gallery). Or [download](https://github.com/novergeme/GTM-template-tag-vk-pixel-retarget-demo/archive/refs/heads/main.zip) the template directly from github and install it in GTM via "Import" templates, [import instructions](https://developers.google.com/tag-manager/templates?hl=ru#export_and_import).

## 2. Setting the tag in the "Conversions" mode

2.1. In the "Enter VK pixel ID" field, enter your VK pixel ID;

2.2. Select the "Conversion (Goal)" mode;

2.3. In the drop-down list, select the event you want to send to VK (For example, add_to_cart);

2.4. If the event has a value, then check the box "Indicate the value of the conversion Value";

2.4.1. In the text field that appears, specify the "data-level variable" that returns the value of the event;

2.4.2. If you want the value of the event to be calculated automatically, then check the box "Calculate value from dataLayer", but in this case, your "data layer variable" should point to an array, for example ecommerce.checkout.products;

## 3. Setting up a tag in Audiences mode

3.1. In the "Enter VK pixel ID" field, enter your VK pixel ID;

3.2. Select the mode "Collection of audiences (Audience)";

3.3. If you want to send a Hit event, then select the setting “Configure URL and Title (Hit)”;

3.3.1. The URL field is set by default; in the Title field, specify a variable that returns the title of the visited page;

3.4. The event, audience and device_id parameters can be specified selectively or all at once;

3.4.1. Parameters event, audience, device_id can be used together with URL and Title. In this case, the Hit event will be sent for one;

## 4. Setting up a tag in Dynamic Retargeting mode

4.1. The "Dynamic retargeting" mode is available only in the Full version, [more details](https://novergeme.ru/vk_pixel_retarget?utm_source=github&utm_medium=gtm&utm_campaign=instruction4_1)  on the developer's website;

4.2. You can look at the Dynamic Retargeting mode UI and see which fields are used in the Full version;

## 5. Section "About the project"

5.1. Video instruction: 12 video instructions are available to you in screencast mode (video from the screen): [YouTube link](https://youtube.com/playlist?list=PLy7BYWCGI_atdK3qm9rbp2PNaAKfSGp0T);

5.2. Developer:  [link to developer site](https://novergeme.ru/vk_pixel_retarget), this link leads to the web page of the developer's site, which is dedicated to this template.
