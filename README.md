# cs4843a1
## Assignment 1: Deploy a static website using AWS S3 and Cloudfront

### Website URL: [d3bz67olgtfbf2.cloudfront.net](https://d3bz67olgtfbf2.cloudfront.net/)



<p> The infrastructure of my deployed website falls within the uses of AWS' cloud services: S3 Buckets and Cloudfront.
Amazon S3 is an object storage service that stores data as objects within buckets. An object is a file and any metadata that describes the file. A bucket is a container for objects. To store your data in Amazon S3, you first create a bucket and specify a bucket name and AWS Region. Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centers called edge locations. When a user requests content that you're serving with CloudFront, the request is routed to the edge location that provides the lowest latency (time delay), so that content is delivered with the best possible performance. </p>

<p> My website is a simple, basic html styled webpage that contains a video, an image, some basic information, and my contact inforamtion. I used S3 buckets to store my webpages and media content. I then used Cloudfront to deploy my website globally. The heart of AWS CloudFront is the high data transfer rate. My application will get loaded with the blink of an eye without any latency rate. Another advantage of cloudfront and why I used it is because since my website is static, the regional edge locations will manage the cache of static images, stylesheets, and tables. This will help global users be able to load my website smoother. </p>
