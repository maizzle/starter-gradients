# CSS Gradients in HTML emails 🌈

This is the repo for the [How to use CSS background gradients in HTML emails](https://maizzle.com/guides/gradients) Maizzle guide.

## Templates

There are 2 examples included:

- [Promotional](https://github.com/maizzle/starter-gradients/blob/master/src/templates/promotional.html) - using a gradient on an element inside the template
- [Transactional](https://github.com/maizzle/starter-gradients/blob/master/src/templates/transactional.html) - body background gradient

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

#### Tailwind CSS Gradients

Since [v1.7.0](https://github.com/tailwindlabs/tailwindcss/releases/tag/v1.7.0), Tailwind includes CSS gradient utilities. However, these currently only work with CSS variables, which are poorly supported in email clients.

Because of that, this Starter uses the [`tailwindcss-gradients`](https://github.com/benface/tailwindcss-gradients) plugin instead.

## Getting Started

Install the Maizzle CLI:

```
npm install -g @maizzle/cli
```

Scaffold a new project with this starter:

```
maizzle new gradients
```

Alternatively, you may clone this starter directly:

```bash
# remember to install dependencies with `npm install`
npx degit maizzle/starter-gradients
```

## Development

Start a local development server:

```
npm run dev
```

Build for production:

```
npm run build
```

## Documentation

Read the guide: https://maizzle.com/guides/gradients

Maizzle documentation is available at https://maizzle.com
