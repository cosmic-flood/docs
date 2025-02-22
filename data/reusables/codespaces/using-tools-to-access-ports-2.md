### Using curl to access a forwarded port

In a terminal on your local computer, enter:

```
curl ADDRESS -H "X-Github-Token: TOKEN"
```

Replace `ADDRESS` and `TOKEN` with the values you copied previously.

### Using Postman to access a forwarded port

1. Open Postman.
1. Create a new GET request.
1. Paste the address you copied previously as the request URL.

   ![Screenshot of the URL pasted into Postman](/assets/images/help/codespaces/postman-screenshot-url.png)

1. In the **Headers** tab, create a new entry where the key is "X-Github-Token" and the value is the `GITHUB_TOKEN` you copied previously.

   ![Screenshot of the key and token in Postman](/assets/images/help/codespaces/postman-screenshot-key-token.png)

1. Click **Send**.
