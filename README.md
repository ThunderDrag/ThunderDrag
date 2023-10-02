<p align="center">
  <img alt="Title" src="Title.svg" width="100%">
</p>

# **Hello, World! 🖐 I'm ThunderDrag.**
- **🎓 Navigating through my UG in Computer Science.**
- **🚀 Passionate about tech & pushing its boundaries.**
- **🔧 Continuously building. Dive into my projects!**
- [**Twitter**](https://twitter.com/thunder_druk/) [<img width="2%" src="Twitter.svg" title="Twitter" target="_blank" align="center"/>](https://twitter.com/thunder_druk/)
- **Technologies I'm Proficient In:**

| Frontend | API | Backend |
| :---: | :---: | :---: |
|<img src="html.svg"><img src="css.svg"><img src="javascript.svg">|<img src="graphql.svg">&nbsp;<img src="rest.svg">|<img src="backend.svg">|


# **My Projects:-**
## 🎭 [Jokes API](https://github.com/ThunderDrag/JokesAPI/)

### 🌟 **About the API:**

This API fetches a random joke from its database. To access it, you'll need a valid authentication token. Without one, you'll face an HTTPS Status Code 401 error.

Here's what sets it apart:
- Exception handling 🛠️
- Detailed logging 📝
- In the rare event of a server glitch, it'll advise you to pause usage and return an HTTPS Status Code 500 🚫

Under the hood, it's powered by AWS Lambda, AWS API Gateway, and AWS DynamoDB. 🚀

### 📬 **Sample Request Header:**

```
GET /Production/api/jokes HTTP/1.1
Host: h0zensjtaj.execute-api.ap-south-1.amazonaws.com
auth: 0
```

### 🎉 **Sample Successful Response:**

```
{
    "content": "What did the ocean say to the beach? Nothing, it just waved.",
    "authenticationStatus": true,
    "error": null
}
```

### 📌 **Highlights:**

✅ Ensures Proper Authentication <br />
✅ Robust Exception Handling <br />
✅ Comprehensive Logging <br />
✅ Built for Speed 🚀<br />
✅ Delivers Possibly Hilarious Jokes 😂

