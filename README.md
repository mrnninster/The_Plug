# INTRODUCTIONS
Hi everyone my name is Akinsola Adefolahan and I am the author of this repo. I realize that many people value their time and i wouldn't want to waste that so I will be straight to the point. The plug is a service that provides you with the ablity to host your neural networks without the need of setting up a server, and providing you an personalized API endpoint to which you can make request and receive responses. All of this process has been designed to take you 10 minutes at most. This is a paid service but there is no payment integration at the moment so  its currenly running free.

## SUPPORT
- At the moment the API end points are able to handle images, list of values or integers **POSTED VIA POSTMAN** to the end points, *GET* request are not allowed. 

- We are only currenly providing support for the TENSORFLOW lITE FILES('.tflite') and the normal KERAS architecture('.h5')

- A limit of 20mb per model has been placed on eaxh instance of the model, because of this TFLite models are highly advised.

- Code snippets for integration into your webapps will be made available in this repo as well.

- I haven't spent much time on the U.I design so the dashboard is still make shift but all the functionalities you should be able to carry out are in view.

## HOW TO USE
There are are currently 3 endpoints you can make use of
 - The test Endpoint 
 This allows you to check the validity of your api, the intention is that this is used post deployment to prevent unnecessary charges

- Integer/List Endpoint
This is desired for users who have regression neural networks.The assumed dimension are 1 X M, where 0<M

- Image Endpoints
This is the end point for image infrence, it takes in greyscale ianges or RGB inages and can be specified using the channels. The images are assumed to be a perfect square of length N x N
