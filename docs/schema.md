# Schema Information

## users
column name     | data type | details
----------------|-----------|-----------------------
id              | integer   | not null, primary key
email           | string    | not null, indexed, unique
username        | string    | not null, indexed, unique
password_digest | string    | not null
session_token   | string    | not null, indexed, unique

## albums
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
user_id     | integer   | not null, foreign key (references users), indexed
title       | string    | not null
description | text      |

## photos
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
title       | string    | not null
url         | string    | not null
exif_data   | string    |
user_id     | integer   | not null, foreign key (references users), indexed
album_id    | integer   | not null, foreign key (references albums), indexed

## comments
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
body        | string    | not null
user_id     | string    | not null
photo_id    | string    | not null

## tags
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
name        | string    | not null
photo_id    | integer   | not null, foreign key (references photos), indexed
