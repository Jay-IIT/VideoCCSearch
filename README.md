# VideoCCSearch

 

 
 

For instance, if I were to upload a 2 minute clip of a music video, your application should parse it, apply subtitles to it and ensure that searching for a particular word or phrase returns the time segment within which the video has those phrases being mentioned.

1)You need to use the ccextractor binary for extracting subtitles from video. Note that using any API, etc for subtitle extraction is not allowed.

2) Further, after processing, the videos need to be stored in S3 and the search keywords (subtitles) in DynamoDB.

3) HTTP requests should have a maximum latency of approx 1 second.

4) The backend should be preferably written in Django. You can use technologies like Celery for background tasks.
 
 
 