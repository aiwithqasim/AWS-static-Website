<h1>Deploy Static Website on AWS</h1>

Screenshots showing steps for Deploying Static Website on AWS.

The following activities has been performed:

<ol>
  <li>All website files are added to the S3 bucket.</li>
  <li>The bucket configuration is set up to support static website hosting.</li>
  <li>The S3 bucket is configured to support static website hosting.</li>
  <li>The permission access to the bucket is configured to allow public access.</li>
  <li>The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.</li>
</ol>

Website Distribution:

The website is distributed via Cloudfront. CloudFront has been configured to retrieve and distribute website files.

<h3>Site Url:</h3>

<a href = "http://d21syuvd0qqu8d.cloudfront.net/" target = "_blank">Qasim's Travelog</a>

<h3>CloudFront Distribution:</h3>

<a href = "https://qasim-hassan.s3.amazonaws.com/index.html" target = "_blank">Qasim's Travelog</a>

<img src = "./Website Overview.jpeg">
