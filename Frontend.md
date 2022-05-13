# Frontend pages

### Member section
Ambigious

### Top bar
1. Close Sidebar
2. Develop notes
3. User Login Modal Button

### Login Popup Modal
1. Click top right button on top bar for login popup
2. email, password, login
3. create new account
4. (research on email verification)
5. forgot password email recovery?

### Edit mdx
Choose tree: Connect, Connect -> Youth Group, Get Involved -> Serving
Edit mdx on current mdx

### Edit blogs post
Any admin or write user can edit or add any blog posts, and but it will not overwrite the author, or time.

### Side bar
Static

### Home
1. Custom page
2. Static Picture flowing
3. Mdx content: Welcome, Kids, Youth, Young Adults
4. Dynamic content: Blogs, Messages (sermons), calendar
5. Static content: offering

### About
Type: MDX list with 1 static picture

Static bible picture serve in frontend
1. Vision
2. Beliefs
3. History
4. Leadership

### Blog
```json
[
    {
        "title": "The drawing of indestructible joy",
        "body": "...",
        "date": "date ISO",
        "author": {"name": "Paster Young", "uid": ""},
        "comments": [
            {
                "author": {"name": "Joseph", "uid": "visitor"},
                "body": "..."
            }
        ]
    }
]

```

### Connect
Type: MDX tree

mdx in utf-8
```text
|-- Connect (manually store the picture on S3 bucket)
|   |-- Children's Ministry
|   |-- Youth Group
|   |-- Young Adults
|   |-- Abundant Life
```

### Get Involved
Type: MDX list with 1 static picture
1. Membership: mdx in utf-8
2. Serving: mdx in utf-8
3. Missions: mdx in utf-8

### Calendar
embed google calendar

### Sermons
1. sermons: (ideas: use special verse syntax to link to external bible?)
```json
[
    {
        "title": "Letter on Comfort",
        "key_verse": "Revelation 2:8-11",
        "vod": "https_link",
        "date": "date ISO format",
        "tags": ["Letters to the Church"]
    }
]
```
2. Discipleship Traning: mdx in utf-8
3. Articles: nearly static: mdx in utf-8
4. Gospel Presentations: mdx in utf-8

### Give
External Link

### Contact us
Static content
Embed Google maps