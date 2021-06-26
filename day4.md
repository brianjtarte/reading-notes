# Day 4 Reading Notes

*Day 4* focused on learning all about HTML, with a little exposure to CSS. 

Two ***main components*** of designing a page with HTML are:

1. Wireframes
2. HTML 

## Wireframes ##

A wireframe is essentially a blue print for a website, representing the desired layout that helps the creator build the framework for their web page.

Keep it simple when designing
More detail can be distracting

Take the time to refine the wireframe after you create the initial one as you may find the first attempt doesn't quite fit/flow right

Ensure you consider user flow when designing, it can be wise to work with a fellow designer

Remember not to worry about aesthetics as a UI designer will ultimately address that issue

## HTML ##

### What is HTML? ###

It stands for Hyper Text Markup Language; in layman's terms, it is a text language that allows the user to structure a webpage. 

### HTML Elements ### 

An HTML element can be broken down into 4 main components:

1. The opening tag: The name of hte element we are using wrapped in opening/closing angle brackets. This tag indicates where the element begins.
2. The closing tag: It is nearly identical to the opening tag, however, it contains a forward slash before the element name. This indidcates where the element ends.
3. The content: This is the content we are including within the element. It can be text, pictures, hyperlink, etc.
4. ***THE*** element: The previous 3 parts combined comprise our element.

You can nest elements within each other, to add emphasis or other characteristics to your element.

### HTML Document Makeup ###

!DOCTYPE html

html

  head

    meta charset="utf-8"

    title>My test page/title

  /head

  body

    img src=images/firefox-icon.

    png alt="My test image">

  /body

/html

DOCTYPE = Required preamble to make sure page operates correctly

HTML = Root element, containing the entire page

Head = This element is a container for items you do NOT want your audience to view. Typically, within this element, we put a page descriptor that would show in search results.

Meta charset = Sets the character set to UTF-8, which includes most characters from majority of written language

Title = Title of page, appaears on the browser tab the page is loaded in

Body = This element is where ALL the content that you want to show to web users goes

Semantics refers to the meaning of a piece of code. There are roughly 100 semantic elements available.