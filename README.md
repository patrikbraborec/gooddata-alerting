# GoodData Alerting

The example repository of alerting with GoodData Python SDK. For more information, please check the [tutorial](docs/tutorial.md).

## Setup Virtual Environment

The following code snippet shows how you can setup virtual environment. You should have installed `virtualenv`.

```bash
# Create virtual env
$ python -m virtualenv venv
# Activate virtual env
$ source venv/bin/activate
# You should see a `(venv)` appear at the beginning of your terminal prompt indicating that you are working inside the `virtualenv`.
# Deactivate virtual env once you are done
$ deactivate
```

## Install Dependencies

```bash
$ pip install -r requirements.txt
```

## Setup of S3

If you do not know how to setup S3, you can find useful the following link [s3 setup](https://realpython.com/python-boto3-aws-s3/#installation).

## Setup Environment Variables

```bash
export GOODDATA_HOST='<gooddata-host>'
export GOODDATA_TOKEN='<gooddata-token>'
export GOODDATA_WORKSPACE_ID='<gooddata-workspace-id>'
export S3_ACCESS_KEY_ID='<s3-access-key-id>'
export S3_SECRET_ACCESS_KEY='<s3-secret-access-key'
export S3_BUCKET_NAME='<s3-bucket-name>'
export EMAIL_PASSWORD='<email-password>'
```
