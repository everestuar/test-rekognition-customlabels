
# Description

* rekognition-detect-text-simple: Python code to detect text on an image. Local execution.
* rekognition-analyze-image: Python code to detect Custom Labels on an image. Local execution. Adjust _model_ variable accordingly.
* lambda-demo-rekognition: Detection of Custom Labels triggered by an image uploaded onto an S3 Bucket. Then inserts the response into a DynamoDB Table.

## To-Do

* Fix pillow error to be able to show image after analysis.

## Reference

> * https://docs.aws.amazon.com/rekognition/latest/dg/what-is.html
> * https://docs.aws.amazon.com/rekognition/latest/dg/text-detecting-text-procedure.html
> * https://docs.aws.amazon.com/rekognition/latest/dg/API_BoundingBox.html
> * https://docs.aws.amazon.com/AWSJavaSDK/latest/javadoc/index.html
> * https://docs.aws.amazon.com/code-samples/latest/catalog/java-rekognition-rekognition-image-java-detect-text.java.html
> * https://docs.aws.amazon.com/rekognition/latest/customlabels-dg/cd-ground-truth.html
