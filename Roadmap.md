# Phase 1

Static content entirely
UI focus
Goal: to make it looks as good as the sample website

### DevOps
Terraform s3 + cloudfront deployment

### Checklist
Webpages: Home, ...
Do mockup first

# Phase 2

Frontend, Backend, Database
Seed admin endpoint (curl with super password)
Seed 3 Admins account: Joseph, Eric, Pastor Young
User create basic account + email activate endpoint + admin promote to write
User login (basic information)

### DevOps
Terraform api-gateway + lambda + dynamoDB deployment
### Checklist
Endpoints: POST /seed-admin, POST /create-account, POST /login, GET /promote-list, POST /promote, POST /email-confirmation
Webpages: login modal (create account), account info, email confirmation clickable (?create-account-token=uuidv4), admin account promotion page (only reachable for admin)

# Phase 3
Admin and Write user can post stuff here
Posting announcement + public/login user comments
Posting sermon links + search sermons + public/login comments on sermon

### Checklist
Endpoints: POST /annoucements, GET /annoucements, POST /annoucements-comments, POST /sermons, GET /sermons, POST /sermons-comments
Webpages: annoucements, sermons (frontend search and sort)

# Phase 4
Advance member account functionality: Ministry Info
Prayer request  (public/priate)
Questions & Answers

### Checklist
Endpoints:  POST /prayer-request (scope selection), GET /prayer-request (member only), POST /question (public only), GET /questions, POST /question-comments (member only)
Webpages: prayers, questions

# Phase 5
Integrate parts together to refine and enhance the experience