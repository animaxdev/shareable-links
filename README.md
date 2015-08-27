# Share Links

![share-links](https://cloud.githubusercontent.com/assets/499192/9524299/8315b54a-4cde-11e5-830a-34b3c4eb8bac.png)

Collection of social media `share-links`. Do you know of another service? Please see the [contributing guidelines](CONTRIBUTING.md) and create a pull request.

- [Buffer](#buffer)
- [Delicious](#delicious)
- [Facebook](#facebook)
- [Flattr](#flattr)
- [Google Bookmarks](#google-bookmarks)
- [Google Plus](#google-plus)
- [Hacker News](#hacker-news)
- [LinkedIn](#linkedin)
- [Pinterest](#pinterest)
- [Reddit](#reddit)
- [Renren](#renren)
- [Sina Weibo](#sina-weibo)
- [StumbleUpon](#stumbleupon)
- [Tumblr](#tumblr)
- [Twitter](#twitter)
- [Vkontakte](#vkontakte)
- [Xing](#xing)

## Buffer
- URL: https://bufferapp.com/add
- Documentation: https://buffer.com/extras/button
- Parameters: `url`, `text`

```
https://bufferapp.com/add?url=https://example.com&text=This+is+the+content
```

## Delicious
- URL: https://delicious.com/post
- Documentation: https://delicious.com/tools
- Parameters: `url`, `title`, `notes`

```
https://delicious.com/post?url=https://example.com&title=This+is+the+title&notes=This+is+the+content
```

## Facebook
- URL: https://facebook.com/sharer.php
- Documentation: https://developers.facebook.com/docs/sharing/reference/share-dialog
- Parameters: `app_id`, `link`, `u`

```
https://facebook.com/sharer.php?app_id=123456789&u=https://example.com
```

## Flattr
- URL: https://facebook.com/sharer.php
- Documentation: http://developers.flattr.net/auto-submit/
- Parameters: `user_id`, `url`, `title`, `content`, `description`, `language`, `tags`, `hidden`, `category`

```
https://flattr.com/submit/auto?user_id=account&url=https://example.com&title=This+is+the+title
```

## Google Bookmarks
- URL: https://www.google.com/bookmarks/mark?op=edit
- Documentation: Not Found
- Parameters: `annotation`, `bkmk`, `labels`, `op`, `title`

```
https://www.google.com/bookmarks/mark?op=edit&bkmk=https://example.com&title=This+is+the+title&annotation=This+is+the+content&labels=one,two
```

## Google Plus
- URL: https://plus.google.com/share
- Documentation: https://developers.google.com/+/web/share/
- Parameters: `url`

```
https://plus.google.com/share?url=https://example.com
```

## Hacker News
- URL: https://news.ycombinator.com/submitlink
- Documentation: https://news.ycombinator.com/bookmarklet.html
- Parameters: `u`, `t`

```
https://news.ycombinator.com/submitlink?u=https://example.com&t=This+is+the+title
```

## LinkedIn
- URL: https://linkedin.com/shareArticle
- Documentation: https://developer.linkedin.com/docs/share-on-linkedin
- Parameters: `url`, `title`, `mini`, `summary`, `source`

```
https://linkedin.com/shareArticle?url=https://example.com&title=This+is+the+title
```

## Pinterest

- URL: https://pinterest.com/pin/create/bookmarklet
- Documentation: https://developers.pinterest.com/docs/pin-it/
- Parameters: `media`, `url`, `description`

```
https://pinterest.com/pin/create/bookmarklet?media=http://example.com/image.jpg&url=http://example.com&description=This+is+the+content
```

## Reddit
- URL: http://reddit.com/submit
- Documentation: https://www.reddit.com/buttons
- Parameters: `url`, `title`

```
https://reddit.com/submit?url=http://example.com&title=This+is+the+title
```

## Renren
- URL: http://widget.renren.com/dialog/share
- Documentation: http://dev.renren.com/website/?widget=rrshare
- Parameters: `url`, `title`, `description`

```
http://widget.renren.com/dialog/share?resourceUrl=https://example.com&title=This+is+the+title&description=This+is+the+content
```

## Sina Weibo
- URL: http://service.weibo.com/share/share.php
- Documentation: http://open.weibo.com/wiki/ShareCode
- Parameters: `url`, `title`

```
http://service.weibo.com/share/share.php?url=https://example.com&title=This+is+the+title
```

## StumbleUpon
- URL: http://www.stumbleupon.com/submit
- Documentation: Not Found
- Parameters: `url`, `title`

```
http://www.stumbleupon.com/submit?url=https://example.com&title=This+is+the+title
```

## Tumblr

- URL: https://www.tumblr.com/widgets/share/tool
- Documentation: https://www.tumblr.com/docs/en/share_button
- Parameters: `posttype`, `url`, `canonicalUrl`, `title`, `caption`

```
https://www.tumblr.com/widgets/share/tool?canonicalUrl=https://example.com&posttype=link&title=This+is+the+title&caption=This+is+the+content
```

## Twitter

- URL: https://twitter.com/share
- Documentation: https://dev.twitter.com/web/intents
- Parameters: `text`, `url`, `hashtags`, `via`, `related`, `in-reply-to`

```
https://twitter.com/share?url=https://example.com&text=This+is+the+content&via=account&hashtags=one,two
```

## Vkontakte
- URL: http://vk.com/share.php
- Documentation: http://vk.com/dev/share_details
- Parameters: `url`

```
http://vk.com/share.php?url=https://example.com
```

## Xing
- URL: https://www.xing.com/spi/shares/new
- Documentation: https://dev.xing.com/plugins/share_button/docs
- Parameters: `url`

```
https://www.xing.com/spi/shares/new?url=https://example.com
```

## License

Share Links is licensed under [The MIT License (MIT)](LICENSE).
