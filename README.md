## Jets S3 Events Example

This project shows a simple IoT button example with Jets.

## Usage

    git clone https://github.com/tongueroo/jets-iot-button-example demo
    cd demo
    # edit .env with your actual values
    bundle

Update [.env](.env) with your own values. Example .env:

    S3_BUCKET=my-own-bucket-name

## Deploy

Next, we'll deploy the app to AWS Lambda with [jets deploy](http://rubyonjets.com/reference/jets-deploy/).

    jets deploy

Here's the blog article:

* Blog Post: []()

If you find Jets interesting, please it a GitHub star [tongueroo/jets](https://github.com/tongueroo/jets). It helps others find out about the project.  I'd appreciate it!