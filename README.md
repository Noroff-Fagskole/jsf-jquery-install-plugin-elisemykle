# Install and use a JQuery plugin

Install and use the TimeDropper JQuery plugin.  Following the instruction on the website, displaying the same example that they give in the simple installation steps.

https://felicegattuso.com/projects/timedropper/

**Note:** Styles are provided for you in master.css. Look in the file to find the approriate class names to use on your HTML elements.

### Example

[The example is here](https://jsf-jquery-install-plugin.now.sh).

## Task

Clone or download this repository onto your computer.  You will start out in the "master" branch which contains an empty project.

Try to recreate the website above.  Firstly, try to create it without any help.  If you are unsure of what to do, you can follow the steps below.  If the steps don't help, checkout out the "answer" branch from this repository.  The answer branch contains a working example.

## Steps

1. Include the jQuery library in your page, either by using CDN, or by downloading the script into your project.  If saved locally the src will be a relative URL to that file.
1. Download the plugin files and add them into your project.  Move the .js file into your JavaScript folder and the .css file into your CSS folder.  Other than the LICENCE, the rest of the files can be removed.
1. Include the CSS and script into the page.  Make sure the script is included after the JQuery script.
1. Add a text input element into the HTML body.
1. From a script at the end of the body tag, apply the plugin to the text input element by selecting the text input with JQuery, and then calling the timeDropper() method on the selected element.
1. Test the output matches the example.