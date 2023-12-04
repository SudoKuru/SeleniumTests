# Deployment styles

Resources:
- https://www.testenvironmentmanagement.com/deployment-styles-bluegreen-canary-and-ab/
- https://blog.bitsrc.io/understanding-when-to-use-blue-green-canary-ab-testing-strategies-54e9bd65cfa6
- https://medium.com/@kazimozkabadayi/exploring-blue-green-deployment-a-b-testing-and-canary-release-161c5e588de0
- [Amazon Describes Deployment strategies](https://docs.aws.amazon.com/whitepapers/latest/overview-deployment-options/deployment-strategies.html)
- https://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/
- https://belowthemalt.com/2021/11/19/a-b-testing-vs-canary-release-vs-blue-green-deployment/

## Deployment types

- Blue/Green
- Canary
- A/B

## Resources
- [Hypertune](https://www.hypertune.com/pricing)

## Web

### Vercel

- [Can do A/B testing using edge middleware](https://vercel.com/guides/ab-testing-on-vercel)

### Netlify

- [Can do split testing (A/B testing)](https://docs.netlify.com/site-deploys/split-testing/). Limitation is that it must be handled with two seperate Git branches using branch deploys.


### Cloudflare Pages

[Can use web workers to implement A/B testing for website](https://developers.cloudflare.com/pages/how-to/use-worker-for-ab-testing-in-pages/)

### Amazon S3

- [Can perform A/B testing using Evidently](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Evidently-sample-application.html)
- [Can perform A/B testing using Lambda Edge](https://medium.com/@emmanuel_87397/case-study-ab-testing-a-static-website-hosted-on-aws-s3-using-cloudfront-and-lambda-edge-0838ac926a11)

## Mobile

### Amazon

- [Supports staged rollouts after 10k downloads](https://developer.amazon.com/docs/app-submission/release-updates-in-staged-rollouts.html)

### Google Play

- [Supports A/B testing for marketing materials](https://support.google.com/googleplay/android-developer/answer/12053285?hl=en)
- https://appradar.com/blog/app-ab-testing-with-store-listing-experiments-in-google-play

- [Supports staged rollouts](https://support.google.com/googleplay/android-developer/answer/6346149?hl=en)


### Apple Appstore

- [Supports A/B testing for marketing materials](https://appradar.com/blog/app-ab-testing-with-product-page-optimization-in-apple-app-store)

- [Supports staged rollouts](https://developer.apple.com/help/app-store-connect/update-your-app/release-a-version-update-in-phases)
