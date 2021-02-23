---
title: 'Configuration of Terms'
date: '2019-11-07T07:46:02+00:00'
weight: 7
---

Once you have created an **attribute**, you have to add variations of it. Click on the button shown to enter the first variation.

![Configure Terms](../images/configure_terms.png "Configure Terms") 

To **add a new color**, specify the following required options:

- **Name :** Color name (shown in frontend).
- **Slug :** Slug for attribute variation.
- **Description :** Description associated to the attribute variation, shown in front end.
- **Colorpicker :** Choose the color you want to assign to the current attribute variation using a colorpicker.
- **Tooltip :** Tooltip associated to the attribute variation and shown in product page.

![Add Attribute Terms](../images/add_attribute_terms.png "Add Attribute Terms") 

You need to specify **{show_image}** for the attributes of image type in **Tooltip** entry if you want to show as tooltip the selected image preview for that specific term.   
 *Note :* Only available for Image type.


![Placeholder {show_image}](../images/show_image.png "Placeholder {show_image}")

![Output after adding {show_image}](../images/show_image_front.png "Output after adding {show_image}")

In our example, we have entered the following colors:

- Blue
- Red
- Black/Red
- Gray
- Gray/Blue
- Red/Blue

![WooCommerce Color Variation](../images/color_variation.png "WooCommerce Color Variation")

You can create new product **variations** directly from product detail page.

Open a **product**. Then add an attribute & click on **Add** to add a new variation.

![WooCommerce Variation Settings](../images/add_new_variation.png "WooCommerce Variation Settings")

In our example, the attribute type is “colorpicker” and, therefore, in the modal window that opens we will have to add colours for the new variation.

![WooCommerce Variation Settings](../images/add_new_variation2.png "WooCommerce Variation Settings")

**WooCommerce Variation Swatches** plugin allows to configure a term for the attribute by matching two colors.

Click on the specific button to select the ***second color***.

![WooCommerce Variation Settings](../images/2colors_term.png "WooCommerce Variation Settings")

Product’s frontend output using **WooCommerce Variation Swatches** for the attribute by matching two colors.

![WooCommerce Variation Settings](../images/2colors.png "WooCommerce Variation Settings")