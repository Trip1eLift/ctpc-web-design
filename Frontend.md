# Frontend pages

### Member section
Ambigious

### Top bar
Close Sidebar
Develop notes
User Login Modal Button

### Login Popup Modal
Click top right button on top bar for login popup
email, password, login
create new account
(research on email verification)
forgot password email recovery?

### Edit mdx
Choose tree: Connect, Connect -> Youth Group, Get Involved -> Serving
Edit mdx on current mdx

### Edit blogs post
Any admin or write user can edit or add any blog posts, and but it will not overwrite the author, or time.

### Side bar
Static

### Home
Custom page
Static Picture flowing
Mdx content: Welcome, Kids, Youth, Young Adults
Dynamic content: Blogs, Messages (sermons), calendar
Static content: offering

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
|-- Connect (manually store the picture on S3 bucket)
|   |-- Children's Ministry
|   |-- Youth Group
|   |-- Young Adults
|   |-- Abundant Life

### Get Involved
Type: MDX list with 1 static picture
1. Membership: mdx in utf-8
2. Serving: mdx in utf-8
3. Missions: mdx in utf-8

### Calendar
embed google calendar

### Sermons
GET /sermons
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