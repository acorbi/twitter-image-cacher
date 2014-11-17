twitter-image-cacher
====================

PHP script returning URL for twitter's image of user specified by parameter. In order to save up calls to the Twitter API, results are cached as text files.

# Installation

First you need to create a Twitter app under https://apps.twitter.com/

1. Rename config.php.sample to config.php and specify Twitter APP credentials.
2. Deploy PHP files on a webserver of your choice.

# How to use

Client has to GET-Request the twitter_profile_retriever.php file setting the **screen_name** parameter with the twitter handle, example:

```
GET http://server/twitter_profile_retriever.php?screen_name=acorbi
```

The script will return the URL of the twitter image in plain text:

```
http://pbs.twimg.com/profile_images/1113334395/Screen_shot_2010-08-26_at_1.48.20_AM_normal.png
```

# Used in

https://github.com/acorbi/ok-directory-public

# Uses

James Mallison <me@j7mbo.co.uk>
Twitter-API-PHP
http://github.com/j7mbo/twitter-api-php
