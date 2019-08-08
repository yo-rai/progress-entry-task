Dear Olivia,

Thank you for contacting us. I would be more than glad to assist you with resolving any difficulties you might be experiencing.

I believe what best could suit your needs is the Kendo UI for jQuery and more specifically the Grid widget. Its power is focused in displaying big and small amounts of data equally useful. Furthermore, basic functionalities include filter menu, selection of rows while sorting and filtering, row grouping, pagination in both server and client-side and more. 

To begin with let me verify with you that you have the appropriate setup. A prerequisite would include an IDE of your choice (I am personally using Visual Studio Code).

<b>Step 1:</b>
To install Kendo UI for jQuery widgets, you can use the available Kendo UI CDN services which are hosted on Amazon CloudFront. Another option would be to use the Node package manager, NuGet, Bower or a CDN. Please refer <a href=https://docs.telerik.com/kendo-ui/intro/installation/overview-download>to this document</a> for more information on installation.

<b>Step 2:</b>
Proceed and add all Kendo UI css, js and jQuery paths in the head section of your respective HTML file.
Could be done as below if using CDN:
<img src="https://scontent.fsof10-1.fna.fbcdn.net/v/t1.0-9/67736248_10156554407517616_6521438910151655424_o.jpg?_nc_cat=103&_nc_oc=AQk75GhfHs4l5uUIRjPBK4XyJnvbCImMjjzVo2PKSb2YiCE2PiZrDkAlTQIeDdgYdCs&_nc_ht=scontent.fsof10-1.fna&oh=7759dd4f4db2439eacd22a0c144d98db&oe=5DA00C74">

<b>Step 3:</b>
Add selector in HTML page so that the grid can be bound to that element as shown below:
<img src="https://scontent.fsof10-1.fna.fbcdn.net/v/t1.0-9/67929064_10156554410917616_2657549630450958336_o.jpg?_nc_cat=109&_nc_oc=AQkw3uUbfNQ2PXsG19G9IOPmUWySZBskpz7OTKS4UtwxHFf2JxYBfKGNORIdwZ9kNBU&_nc_ht=scontent.fsof10-1.fna&oh=0f87de2c7a7294f56787877786b970a6&oe=5DD9B0E7">

<b>Step 4:</b>
Now it is time to configure the grid itself to DOM element (#grid) and here how it is done and could be adapted according to your personal needs:
<img src="https://scontent.fsof10-1.fna.fbcdn.net/v/t1.0-9/68482116_10156554420357616_2366986197999288320_o.jpg?_nc_cat=106&_nc_oc=AQmhfI2Ms8VeoL2VwOkzM8vuT0TQHfreazH1zVcR65Ra2gBgL6nb8a4Dd2TxkHeluGg&_nc_ht=scontent.fsof10-1.fna&oh=68297315548dada008f689a1edd478bc&oe=5DDCB55E">

The data source could be dynamic or static. The example above demonstrates how to specify the field attribute in the column array so that the Grid displays the required data from the response. The columns also have a title property which provides more user-friendly header titles for the columns.

<b>Step 5:</b>

For further tuning, please refer to the following links:

<a href="https://docs.telerik.com/kendo-ui/controls/data-management/grid/overview">Grid Overview and Details</a>

<a href="https://demos.telerik.com/kendo-ui/grid/index">Kendo UI for jQuery Demo</a>

<a href="https://www.telerik.com/blogs/how-to-use-a-jquery-grid-ui-component-in-your-web-app">How to use a jQuery grid component in your web app</a>



I hope I have been helpful. Please, do not hesitate to contact me with further questions that might arise.


Kindest regards,

Yoana


