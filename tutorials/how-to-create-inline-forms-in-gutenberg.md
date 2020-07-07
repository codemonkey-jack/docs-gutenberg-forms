# How to create inline forms in Gutenberg

Creating any form layout with Gutenberg form is super easy. It comes with a "**Form Columns**" block which you can use to create any layout. Let's see how easy it is to create an inline form using it. 

**Here is a step-by-step tutorial.**

If you are creating the form directly on a page, post or CPT add the Gutenberg Forms block. And if you are creating it via the "**Forms**" screen, ignore this step. 

![](../.gitbook/assets/image-2020-07-07-at-1.52.20-pm.png)

Now click on the standard button that will insert a basic standard form. You can then remove extra fields and add need fields/blocks.

![](../.gitbook/assets/image-2020-07-07-at-2.00.24-pm.png)

For this tutorial we will create a form with the following fields:

* Name
* Email
* Button

So we can simply remove the Message field from the standard form. We also need to disable the default submit button as we need to place it inside a column. 

Simply select the main form block and from the sidebar settings, you can disable it under the "General" settings panel.

![](../.gitbook/assets/screen-recording-2020-07-07-at-02.03.14-pm.gif)

Now let's add a **form columns** block and add 3 columns. 

![](../.gitbook/assets/screen-recording-2020-07-07-at-02.07.25-pm.gif)

Now drag the name and email fields in each column.

![](../.gitbook/assets/screen-recording-2020-07-07-at-02.08.56-pm.gif)

Finally, add a "**Form Button**" block in the last column. 

![](../.gitbook/assets/screen-recording-2020-07-07-at-02.09.28-pm.gif)

That's it! we have created an inline form with 3 columns. You can add more columns if you wish. And style the button or fields using the customization options available in the sidebar.

This is how it looks on the front-end for the **Tweenty TweentyTheme**. Your output may be different depending on the theme you are using.  

![](../.gitbook/assets/image-2020-07-07-at-2.12.43-pm.png)

The button sticks on the top of the column as other content. You may either use custom CSS to align it to the bottom vertically. Or simply use a spacer block above it to add spacing from the top.

![](../.gitbook/assets/screen-recording-2020-07-07-at-02.16.54-pm.gif)

This is how it looks on the front with the spacer added and some colors applied to the button.

![](../.gitbook/assets/image-2020-07-07-at-2.18.45-pm.png)

You may also be interested in removing the label and adding it as a placeholder. Check out these two posts for that.

{% page-ref page="../quick-tips/how-to-disable-field-labels.md" %}

{% page-ref page="../quick-tips/how-to-add-a-placeholder-text-to-an-input-field.md" %}

Hope that was helpful. 😇

