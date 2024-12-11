# tour-and-travel-server

1. user
2. tour
3. review

user {
name
email
age
photo
role -> user, admin
status -> active, inactive
}

tour {
name
duration
rating
price
cover-image
image[]
start-date
tour-location
}

review {
review-text
rating
tour -> ref
user -> ref
}
