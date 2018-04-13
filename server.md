# Server Architecture

There are many options when selecting the right server architecture. But I will point out few of them keeping in mind the Size of the application. Many times we may have to take alternate cource of action if needed.

> I am not going to specify the third-party services. We will have to make adjustments for that.

## Staging and Production servers

We should have 2 different servers for a single project. One for staging and one for production.

Staging server can be low powered but we have to considter significant computing power for the Production server.

## Small & Medium & Big Projects

For small and medium applications a managed server with great support. The best provider I've worked with so far is: [Cloudways](https://www.cloudways.com). They have great support for Number of solutions. Ex. Wordpress, Laravel, Magento, Plain PHP. The best part is we can deploy multiple applications on a single server and we can Scale the applications on the fly whenever required.

They have `24x7 support` and all the Database, PHP and Apache are configurable through a visual interface.

They have numorous cashing solutions, ex `Memcache`, `Varnish`.

Along with that there are multiple services provided by them out of the box like, `Redis`, `ElastiSearch`.

They also have many Laravel related adapters like `Supervisord` Queue job handler, `CRON manager`.


## Huge Applications

For this purpose we have to use custom AWS solutions:

1. EC2.
2. EBS - S3
3. RDS
4. Others.

The possibilities are endless here, we have to adapt to the requirement and solution when needed.
