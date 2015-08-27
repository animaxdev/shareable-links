# Share Links

![share-links](https://cloud.githubusercontent.com/assets/499192/9524299/8315b54a-4cde-11e5-830a-34b3c4eb8bac.png)

Collection of social media `share-links`. Do you know of another service? Please see the [contributing guidelines](CONTRIBUTING.md) and create a pull request.

- [Google Plus](#google-plus)
- [Facebook](#facebook)
- [Pinterest](#pinterest)
- [Twitter](#twitter)

## Google Plus
- URL: https://plus.google.com/share
- Documentation: https://developers.google.com/+/web/share/
- Parameters: `url`

```
https://plus.google.com/share?url=https://example.com
```

## Facebook
- URL: https://facebook.com/sharer.php
- Documentation: https://developers.facebook.com/docs/sharing/reference/share-dialog
- Parameters: `app_id`, `link`, `u`

```
https://facebook.com/sharer.php?app_id=123456789&u=https://example.com
```

## Pinterest

- URL: https://pinterest.com/pin/create/bookmarklet
- Documentation: https://developers.pinterest.com/docs/pin-it/
- Parameters: `media`, `url`, `description`

```
https://pinterest.com/pin/create/bookmarklet?media=http://example.com/image.jpg&url=http://example.com&description=This+is+the+content
```

## Twitter

- URL: https://twitter.com/share
- Documentation: https://dev.twitter.com/web/intents
- Parameters: `text`, `url`, `hashtags`, `via`, `related`, `in-reply-to`

```
https://twitter.com/share?url=https://example.com&text=This+is+the+content&via=account&hashtags=one,two
```

## License

Share Links is licensed under [The MIT License (MIT)](LICENSE).
