# thumber
An exercise in building a simple python thumbnail generation service

### Input video file details 
  A well-formed video file in a container format that `ffmpeg` can read from AWS S3.  You can use any input files you choose for testing.
  If you need an S3 bucket, let us know.

### Instructions
1. Given a video file as above, using ffmpeg, create a thumbnail image from the frame with the highest contrast of the frames in the first 
    3 seconds of the video. The thumbnail should be in original aspect ratio, 200px high in any image format you choose.
2. Design an API for a service that will take this kind of input and create and store the thumbnail back in the AWS S3 
    bucket. Include in your design how the service will report back error and exceptional conditions.
3. Implement a version of this service in Python.
4. Document your work.
