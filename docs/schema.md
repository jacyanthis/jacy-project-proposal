# Schema Information

## users
column name     | data type | details
----------------|-----------|-----------------------
id              | integer   | not null, primary key
email           | string    | not null, unique
password_digest | string    | not null
session_token   | string    | not null, unique

## emails
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
user_id     | integer   | not null, foreign key (references users)
subject     | string    | not null
sender      | string    | not null
recipients  | string    |
body        | string    |
folder      | string    | not null
starred     | boolean   | not null


## chats
column name | data type | details
------------|-----------|-----------------------
# TBD
