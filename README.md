# [LocomotiveCMS](https://github.com/locomotivecms/engine) on [Heroku](http://heroku.com)

LocomotiveCMS is designed to save your time and help you focus on what matters: front-end technology, standard development process and no learning time for your client. Visit the project's website at <http://locomotivecms.com/>, or read the docs on <http://doc.locomotivecms.com/>.

## Deploying on Heroku

To get your own LocomotiveCMS running on Heroku, click the button below:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/locomotivecms/heroku-instant-deploy)

Follow the steps and you will be up and running in no time!

### Things you should know

- After deployment, your site will be publicly accessible at `YOURAPPNAME.herokuapp.com`.

- You can add a custom domain through the [Heroku Toolbelt](https://toolbelt.heroku.com/) or through the website.


### Configuring environment variable

- **HEROKU_APP_NAME (required):** Pick a name for your application.

- **HEROKU_API_KEY (required):** The API key of your Heroku user account. If you need help finding it, you can find it by following this guide: <https://devcenter.heroku.com/articles/authentication>.

- **HEROKU_API_KEY (required)** and **S3_ACCESS_SECRET_KEY (required):** These fields is how your site will authenticate with Amazon S3. To do this, follow this guide <http://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSGettingStartedGuide/AWSCredentials.html>. You also need to make sure that this key pair has sufficient access to your S3 bucket. Follow this guide to make sure this is done: <http://docs.aws.amazon.com/AmazonS3/latest/dev/s3-access-control.html>

- **S3_BUCKET_NAME (required)**. The name you used when creating the S3 bucket.

- **S3_BUCKET_REGION (required)**. Pick the region you selected when setting up AmazonS3 <https://locomotive-v3.readme.io/docs/heroku#set-up-amazon-s3>.

- **S3_BUCKET_REGION (optional)**. Optional custom CDN asset host url.

## Problems?

If you have problems using your instance of Ghost, you should check the [official documentation](http://doc.locomotivecms.com/) or open an issue on [the official issue tracker](https://github.com/locomotivecms/engine/issues). If you discover an issue with the deployment process provided by *this repository*, then [open an issue here](https://github.com/locomotivecms/heroku-instant-deploy).

## License

Copyright (c) 2015 NoCoffee, released under the [MIT license](./LICENSE)