# Cloud Juggler
Toolkit to optimize cost and efifciency on Amazon Web Services.

## Cloud Juggler Budgets - keep your spend within expectations
Let you define rules how much you can spend and alerts with escalations and overrides.

The cloud gives you a lot of superpowers, but it is also easy to spend a lot of money accidentally. Budgets fixes that, let you enjoy the benefits of cloud while making sure that AWS bill wouldn't surprise you.

The default [AWS Budgets](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html) are very limited and don't support many real world scenarios.

Example A:
 1. You plan to spend $500 / month. 
 2. If you are on trajectory to spend more you will be notified by email.
 3. Simple by clicking on link you can allow one-time exception, increase your budget or simple acknowledge situation.
 4. It support escalations, so your company won't miss it simple because you went off-grid.

Example B:
 1. You have a team of 5 developers with 5 AWS development accounts under consolidated billing.
 2. You want to allow each one spend $1000 / month for development as well as have total $4000 / month budget.
 3. Individual developer can take care of her budget. Prevent accidental spent, but also notify tech lead if need higher budget.
 4. Tech lead also takes care of whole team budget. She also get escalation if indivdual developer ignores alert and allocate the resources.

### Tech details

Implemented as serverless application using [API Gateway](https://aws.amazon.com/api-gateway/), [AWS Lambda](https://aws.amazon.com/lambda/), [Amazon SNS](https://aws.amazon.com/sns/) and [S3](https://aws.amazon.com/s3/). 

### How to install

To be implemented. Work in progress.

