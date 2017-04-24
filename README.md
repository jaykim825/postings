# README

1 Users
- Relationships
-  has_many :Postings
-  has_many: Comments
-Elements
 email / password

2 Postings
- Relationships
-   belongs_to :User
-   has_many : Comments
- Elements
- title, content, user_id

3 Comments
- Relationships
-belongs_to :Users
-belongs_to :Postings
- elements
content, user_id, posting_id
_______________________________________________________

# Controllers / views

posting Controller

Comment Controller

User => devise gemfile

_______________________________________________________

# CSS / JS : Bootstrap CDN

