# APIs and Datasets for Scholarly Publications

Using [Lens.org](https://www.lens.org/) APIs and datasets.

## Accessing Data and API

```mermaid
sequenceDiagram
    Actor User
    User ->>+Lens.org: Request access via form
    loop Form
        Lens.org->>Lens.org: Process form
    end
    Lens.org->>+User: email with access details
```

1. Sign in using your KAUST email.
1. Select the type of API or bulk data you are interested in and click `Request Access` to access the online application form.
1. Apply by completing the online application. Make sure to provide accurate information about your use case, affiliation and organization.
1. Upon submission you will receive a confirmation email that your application is now being processed.
1. Your application is received by the Lens team and will be evaluated based on the use-case, commercial or non-commercial use, affiliation or organization size/type. We may contact you for additional information to help in the evaluation.
1. If your application is approved, you will receive another confirmation email that will include instructions on how to access your API token to obtain the data.

## Access Token

The first step to use the Lens.org API is to request token. See the below.

![Lens.org access token](pics/lens_org_request_token.png)

Once you have your token, you can start using the API.

## API Documentation

On the [Lens.org support](https://docs.api.lens.org/), there are two very important documents: [Requests](https://docs.api.lens.org/request.html), and [Reponse](https://docs.api.lens.org/response.html).

We will explore simple requests, and how to process the response. 
