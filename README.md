This is a assignment project done to recognized the type of moving objects in a video footage. The realization is made up of two parts.
First, the video footage is analyzed using OpenCV API and extract the ROI of moving objects. Then, using separate code, the transfer learning model was retrained and finetuned using open source vehicle image dataset.
Last but not least, the finetuned transfer learning model is used to predict the extracted ROI of moving objects and further ensemble learning using majority voting was applied to make the prediction model more robust.
