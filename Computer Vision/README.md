# Computer Vision on Azure

Computer Vision is an area of AI that deals with visual processing. Let's explore some of the possibilities that computer vision brings.

The Seeing AI app is a great example of the power of computer vision. Designed for the blind and low vision community, the Seeing AI app harnesses the power of AI to open up the visual world and describe nearby people, text and objects.

Most computer vision solutions are based on machine learning models that can be applied to visual input from cameras, videos, or images.

## Common Computer Vision tasks

**Image Classification** - Image classification involves training a machine learning model to classify images based on their contents. For example, in a traffic monitoring solution you might use an image classification model to classify images based on the type of vehicle they contain, such as taxis, buses, cyclists, and so on.

**Object Detection** - Object detection machine learning models are trained to classify individual objects within an image, and identify their location with a bounding box. For example, a traffic monitoring solution might use object detection to identify the location of different classes of vehicle.

**Semantic Segmentation** - Semantic segmentation is an advanced machine learning technique in which individual pixels in the image are classified according to the object to which they belong. For example, a traffic monitoring solution might overlay traffic images with "mask" layers to highlight different vehicles using specific colors..

**Image analysis** - You can create solutions that combine machine learning models with advanced image analysis techniques to extract information from images, including "tags" that could help catalog the image or even descriptive captions that summarize the scene shown in the image.

**Face Detection** - Face detection is a specialized form of object detection that locates human faces in an image. This can be combined with classification and facial geometry analysis techniques to infer details such as age and emotional state; and even recognize individuals based on their facial features.

**OCR** - Optical character recognition is a technique used to detect and read text in images. You can use OCR to read text in photographs (for example, road signs or store fronts) or to extract information from scanned documents such as letters, invoices, or forms.

## Computer vision services

Microsoft Azure provides the following cognitive services to help you create computer vision solutions:

**Computer Vision** -	You can use this service to analyze images and video, and extract descriptions, tags, objects, and text.

**Custom Vision** -	Use this service to train custom image classification and object detection models using your own images.

**Face** -	The Face service enables you to build face detection and facial recognition solutions.

**Form Recognizer** -	Use this service to extract information from scanned forms and invoices.

## Try Examples

To see an example of a how computer vision can be used to analyze images, follow these steps:

- Open browser and go to https://aidemos.microsoft.com/computer-vision.
- Use the demo interface to try each of the steps. For each step, you can select images and review the information returned by the Computer Vision service.

## References

https://docs.microsoft.com/en-us/learn/modules/get-started-ai-fundamentals/4-understand-computer-vision