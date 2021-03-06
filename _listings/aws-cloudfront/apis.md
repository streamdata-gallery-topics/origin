---
name: AWS CloudFront
x-slug: aws-cloudfront
description: Amazon CloudFront is a global content delivery network (CDN) service
  that accelerates delivery of your websites, APIs, video content or other web assets.
  It integrates with other Amazon Web Services products to give developers and businesses
  an easy way to accelerate content to end users with no minimum usage commitments.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Origin
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudFront API Create Cloud Front Origin Access Identity
  x-api-slug: aws-cloudfront-api
  description: Creates a new origin access identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=CreateCloudFrontOriginAccessIdentity
  tags: Cloud, Front, Origin, Access, Identity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/actioncreatecloudfrontoriginaccessidentity-get-openapi.md
- name: AWS CloudFront API Delete Cloud Front Origin Access Identity
  x-api-slug: aws-cloudfront-api
  description: Delete an origin access identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=DeleteCloudFrontOriginAccessIdentity
  tags: Cloud, Front, Origin, Access, Identity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/actiondeletecloudfrontoriginaccessidentity-get-openapi.md
- name: AWS CloudFront API Get Cloud Front Origin Access Identity
  x-api-slug: aws-cloudfront-api
  description: Get the information about an origin access identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=GetCloudFrontOriginAccessIdentity
  tags: Cloud, Front, Origin, Access, Identity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/actiongetcloudfrontoriginaccessidentity-get-openapi.md
- name: AWS CloudFront API Get Cloud Front Origin Access Identity Config
  x-api-slug: aws-cloudfront-api
  description: Get the configuration information about an origin access identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=GetCloudFrontOriginAccessIdentityConfig
  tags: Cloud, Front, Origin, Access, Identity, Config
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/actiongetcloudfrontoriginaccessidentityconfig-get-openapi.md
- name: AWS CloudFront API List Cloud Front Origin Access Identities
  x-api-slug: aws-cloudfront-api
  description: Lists origin access identities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=ListCloudFrontOriginAccessIdentities
  tags: List, Cloud, Front, Origin, Access, Identities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/actionlistcloudfrontoriginaccessidentities-get-openapi.md
- name: AWS CloudFront API Update Cloud Front Origin Access Identity
  x-api-slug: aws-cloudfront-api
  description: Update an origin access identity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: ://///?Action=UpdateCloudFrontOriginAccessIdentity
  tags: Cloud, Front, Origin, Access, Identity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/actionupdatecloudfrontoriginaccessidentity-get-openapi.md
- name: AWS CloudFront API
  x-api-slug: aws-cloudfront-api
  description: Amazon CloudFront is a global content delivery network (CDN) service
    that accelerates delivery of your websites, APIs, video content or other web assets.
    It integrates with other Amazon Web Services products to give developers and businesses
    an easy way to accelerate content to end users with no minimum usage commitments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AmazonCloudFront.png
  humanURL: https://aws.amazon.com/cloudfront/
  baseURL: :///
  tags: Origin
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/origin/master/_listings/aws-cloudfront/openapi.md
x-common:
- type: x-analysis
  url: https://aws.amazon.com/cloudfront/reporting/
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonCloudFront/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/cloudfront/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/cloudfront/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudfront/pricing/
- type: x-service-level-agreement
  url: https://aws.amazon.com/cloudfront/sla/
- type: x-webinars
  url: https://aws.amazon.com/cloudfront/webinars/
- type: x-website
  url: https://aws.amazon.com/cloudfront/
- type: x-whats-new
  url: https://aws.amazon.com/cloudfront/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---