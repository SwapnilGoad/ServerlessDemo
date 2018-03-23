npm install -g serverless

Create an IAM User: "serverless-cli" if does not exist;

Copy and Store:

Access-Key-Id: AKIAJ4T6GF4JHV4TOMQA
Secret-Access-Key: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

Run Command:
===================
c:\>sls config credentials --provider aws --key <Access-Key-Id> --secret <Secret-Access-Key>

Example for above user:
==========================
c:\>sls config credentials --provider aws --key AKIAJ4T6GF4JHV4TOMQA --secret eyFcYS8b5dGy8VOm2uAbZ1uVeIfEZwt8NDkfEU86
c:\> md API
c:\> cd API

Generate a Boiler Plate Code for our NodeJS API:
=====================================================
c:\API> sls create --template aws-nodejs

