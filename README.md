# CSS Gradients in HTML emails 🌈

This is the repo for the [How to use CSS background gradients in HTML emails](https://maizzle.com/guides/css-background-gradients-html-emails/) Maizzle tutorial.

## Templates

There are 2 examples included:

- [Promotional](https://github.com/maizzle/example-gradients/blob/master/src/templates/promotional.html) - using a gradient on an element inside the template
- [Transactional](https://github.com/maizzle/example-gradients/blob/master/src/templates/transactional.html) - body background gradient

## Compatibility

The templates use a CSS `background-image` linear gradient with a VML fallback for Outlook, which means it works in over 87% of all email clients (possibly even more, lots of email clients for the Mac should support this just fine).

Email clients that don't support either of those will show a solid background color.

CSS gradient works in:

- Apple Mail
- iOS Mail
- Outlook iOS
- Gmail iOS
- Gmail Android
- Gmail Web, Google Apps (browser)
- Samsung Mail
- Thunderbird
- \+ various other web-based email clients

VML fallback works in:

- Outlook 2007
- Outlook 2010
- Outlook 2013
- Outlook 2016
- Outlook 2019

Solid background color shows in:

- Outlook.com
- Office 365
- Yahoo! Mail
- AOL Mail
- Comcast, GMX, Telstra/BigPond
- Outlook 2003



## Getting Started

Install the Maizzle CLI:

```
npm install -g @maizzle/cli
```

Scaffold a new project with this example:

```
maizzle new maizzle/example-gradients && cd example-gradients
```

Develop locally:

```
maizzle serve
```

Build for production:

```
maizzle build production
```

## Documentation

Read the guide: https://maizzle.com/guides/css-background-gradients-html-emails/

Maizzle documentation is available at https://maizzle.com
