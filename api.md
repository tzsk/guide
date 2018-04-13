# API Development

We will have to have some standards for developing API with in innofied. First I'll use point out some Security Aspects then will talk about the Response Standards.

## API Key

We must have all our endpoints API Key protected. We will have an API Key generated uniquely for each Project. And the Apps will ship with that API key. In the header of every call the APP should send the API-KEY otherwise the request won't get through.

> ```json
{
    "headers": {
        "API-KEY": "..."
    }
}
```

## Token Based Authentication

All the authenticated / proetected routes will have token based authentication. APP will need to send that along with every private API calls to actually get the Data.

> We will use default `token` driver which comes with laravel for authentication but if the project requires it then we can move to `Passport` otherwise passport is not necessary.

## Standards

**1. Repository & Presenter**

In laravel we will have to use `Repository Pattern` with `Presenter` for each page to taylor that response for that specific page. Repository pattern will ease the development and make the presenter easy to implement.

**2. Response Standard**

Every API Response will have the specific set of keys. That will ease out the APP dev process.

The keys shoud be:

> ```json
{
    "status": true,
    "code": 200,
    "message": "Any message",
    "data": []
}
```