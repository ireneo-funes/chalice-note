# chalice-note
Explains how to use AWS (Amazon Web Services) Chalice

## URL
If the current chalice proejct is deployed, you can see its URL by providing the `url` parameter.

```console
~/Desktop/AWS/chalice-test/
(AWS) ❯ chalice url
https://{REST API ID}.execute-api.{AWS Region ID}.amazonaws.com/api/
```
## DELETE

```console
~/Desktop/AWS/chalice-test/
(AWS) ❯ chalice delete
Deleting Rest API: {REST API ID}
Deleting function: arn:aws:lambda:{AWS Region ID}:{Lambda ARN}
Deleting IAM role: {Deleted IAM role}
```
