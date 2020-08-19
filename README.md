# INTRODUCTIONS
Hi everyone my name is Akinsola Adefolahan and I am the author of this repo. I realize that many people value their time and i wouldn't want to waste that so I will be straight to the point. The plug is a service that provides you with the ablity to host your neural networks without the need of setting up a server, and providing you an personalized API endpoint to which you can make post data and receive responses. All of this process has been designed to take you 10 minutes at most. This is a paid service but there is no payment integration at the moment so its currenly running free.

## SUPPORT
- At the moment the API end points are able to handle images, list of values or integers **POSTED VIA POSTMAN** to the end points, *GET* request are not allowed. 

- We are only currenly providing support for the TENSORFLOW LITE FILES('.tflite') and the normal KERAS file format('.h5')

- A limit of 20mb per model has been placed on eaxh instance of the model, because of this TFLite models are highly advised.

- Code snippets for integration into your webapps will be made available in this repo as well.

- I haven't spent much time on the U.I design so the dashboard is still make shift but all the functionalities you should be able to carry out are in view.

## UPLOADING NETWORK
In the top left part of your dashboard interface, there are 3 icons, the first looks like a gear, select this to upload your networks, please fill out all the information

- Project Name
  Name your project will be displayed as to yourself and third parties

- File Type
  The type of network you will be working with.

- Input Type
  In this case you can select either images or Integers
  
- Dimensions(M)
  In the case of the regression type model which is usually a 1 by M dimension input, and M is the dimension specified here
  
- Image Preprocessing
  You can choose if you want to preprocess you images by normalization or not. At the moment you can preprocessing by normalizing to a "0 to 1" range and "-1 to 1" range.
  
- Channels
  For integers or list, this is should set to none, for grey scale type input images this should be 1 and for rgb type input images, this should be set to 3
  
- Model Selection

- Use Case
  
 

## HOW TO USE
There are are currently 3 endpoints you can make use of
 - The test Endpoint 
 This allows you to check the validity of your api, the intention is that this is used pre deployment to prevent unnecessary charges, this can be done using a simple get request as compared to the remaining end point request

- Integer/List Endpoint
This is desired for users who have regression neural networks.The assumed dimension are 1 X M, where 0<M,

- Image Endpoints
This is the end point for image inference, it takes in greyscale images or RGB images and can be specified using the channels. The images are assumed to be a perfect square of length N x N as specified by dimension

Please use the snippets provided so you canconnect properly. However if you still encounter issues you can contact me on twitter using @mrnninster or mail me adefolahan@plugai.xyz. You could also use the message function at the top of your dashboard, this should open up your mail app directly


## RESPONSE
Please be aware that all responses will come as json responses as shown below

![](Screenshot%20(133).png)


## UPDATES 
The Due to a large number of requests I have been getting to provide tutorials that actually explain in details the steps you would take to make use of the platform, and to include other major libraries, like SKLearn, PyTorch, and FastAi as supported libraries I have the following to make public. At the moment tutorials for tensorflow use cases have been added just go the sample implementation section on the website.

Over the next couple of weeks I will be adding tutorials and support for SKLearn as well as FastAi. If you do have contributions to make or request you can mail me or open an issue I will attend to them as soon as I possibly can.

## TENSORFLOW
The models developed during the tensorflow model tutorial process are made available [here](https://drive.google.com/drive/u/0/folders/1CMjQ62miguKaxPzM303PVsr-SRNPYM2O), you will also find the jupyter notebook scripts here as well. It is to guide you as you develop yours.</br>
**NB:** This platform currently runs tensorflow 2.1


## NEXT 
I will be updating the system soon with provision for videos, live feed, audion as well as text, Please give this repo a star if you like this project and remeber to share, also send me your implementations i would love to see what you do with this.
