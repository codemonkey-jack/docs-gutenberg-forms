# Form Settings

## Gutenberg Form Settings

Gutenberg Forms Block has different settings that you can customize for each form you create.

![](../.gitbook/assets/image-2020-06-18-at-4.31.30-pm.png)

Let's have a look at the different form settings.

### Styles

![](../.gitbook/assets/image-2020-06-18-at-4.35.32-pm.png)

Gutenberg forms come with different pre-made styles that you can apply to your form. Simply click on a style to apply it.

{% hint style="info" %}
Theme authors/developers may also quickly register a new style for using the [Gutenberg Styles API](https://developer.wordpress.org/block-editor/developers/filters/block-filters/#block-style-variations).
{% endhint %}

### Form Design

![](../.gitbook/assets/image-2020-06-18-at-4.41.43-pm.png)

Here you can adjust the basic form color scheme. 

### General

![](../.gitbook/assets/image-2020-06-18-at-4.42.14-pm.png)

In the General settings panel you may configure the following options:

* **Form Label** - This is used as the form id and helps you recognize the entries from the entries screen. make sure you change it to something easily recognizable with the form you are creating.
* **Disable Submit Button** - You can disable the default submit button that is placed at the bottom of the form. You can use the "Form Button" block to place a submit button wherever you like inside the form. 
* **Button Alignment** - This is to adjust the alignment of the default submit button.
* **Confirmation Type** - Configure what would you like to happen on successful form submission. You can either display a thank you message or redirect to a URL. 
* **Hide Form On Submission** - If you are showing a success message, you can also hide the form on submission and only show the success message.

### Email Notification

![](../.gitbook/assets/image-2020-06-18-at-4.52.38-pm.png)

Here you can configure the email notification settings easily. It has the following options.

* **From** - You can specify the from name & email \(separated by a comma\) here. By default it picks up your admin user as the sender.
* **To** - The email address where you like to send out the form data.
* **CC** - Email address where you like to send out a copy.
* **BCC** - Another email address where you like to send out another copy.

![](../.gitbook/assets/screen-recording-2020-06-18-at-06.01-pm.gif)

* **Subject** - Write your email subject here.
* **Body** - Here you can define what data you like to receive in the email. By default, it has `{{all_data}}` tag that retrieve all the fields of your form. But, you can remove that and define your own structure by defining only the data you need. 

![](../.gitbook/assets/screen-recording-2020-06-18-at-05.14-pm.gif)

### Form Action

Here you can pick available form actions. A Form action is simply an action that triggers on successful form submission. 

By default, there are currently two actions available.

1. **Record Entries** - Allows you to save the form submission into your website database that you can access via the "Entries" screen.
2. **Email Notification** - This action sends out the form data via the email to the sender\(s\) you configured via the Email Notification settings.

Both actions are enabled by default. If you like to disable anyone simply remove it from the action. So this way you can disable email notification or entries recording for any particular form you create. 

{% hint style="info" %}
There may be more actions available via add-ons or in future updates.
{% endhint %}



### Field Settings

Each field in Gutenberg Editor is technically a Gutenberg Block. So you can easily deal it similar to any Gutenberg Block.

![](../.gitbook/assets/image-2020-04-04-at-2.23.27-pm.png)

#### Edit Label

Simply click on the field label, and replace the text with yours.

![](../.gitbook/assets/screen-recording-2020-04-04-at-02.29-pm.gif)

#### Set Placeholder

If you want to set a placeholder text, simply write it in the input field. And it will be set as a placeholder text.

![](../.gitbook/assets/screen-recording-2020-04-04-at-02.29-pm%20%281%29.gif)

#### Make a field Required & Change Required indicator Text

It is also super easy in Gutenberg Forms to make a field required and change it's indicator text which appears beside the label on the front-end.

![](../.gitbook/assets/screen-recording-2020-04-04-at-02.30-pm%20%281%29.gif)

#### Fields has Styles

Similar to Gutenberg Blocks, Gutenberg Forms Fields also has different styles. Simply check the styles tab and apply a style you need.

![](../.gitbook/assets/screen-recording-2020-04-04-at-02.30-pm.gif)

{% hint style="info" %}
There will be more styles in future. And, you may define your own styles as well.
{% endhint %}

#### You can change Validation Messages

Each field has options to modify the default validation messages. By default it picks the validation messages defined in the main Form Settings. 

![](../.gitbook/assets/image-2020-04-04-at-2.39.56-pm.png)

####  

