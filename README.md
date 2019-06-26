Technical Explanation:
Entire code runs on 3 functions.

First Function readTextFIle ():
I have used XMLHttpRequest which is a built-in browser object that allows making HTTP requests in JavaScript.
Where it creates a new XMLHttpRequest object. Used open () to specify the URL of the resource to request and returning the response from the server as a string if the readystate =4 and status =200 

Second Function getdata ():
I have parsed the imageData and wrote the loop to get all the images from JSON. I have added an Event listener to show a full image. 

Third Function showFullImage ():
I used CSS to create a modal (dialog box) that is hidden by default and used JavaScript to trigger the modal and to display the current image inside the modal when it is clicked on. 

Provide some detail about how they might be implemented if this project was to be released to Redfin's customers on our website:

If more time is available, on your website you can show customers the grid images of happy clients and on click of the image you can show up the pictures of the corresponding houses with their estimations.
As the images are loaded dynamically we can change the images accordingly without any front end changes. On clicking in the client image we can ask them to submit rating for the service you provide. This would be another idea where we can reuse the same design and technical implementation.   
