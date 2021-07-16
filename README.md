# Fonts

> Fonts for the Guardian Digital.

## License

The font files in this repo and the URLs below may only be used on Guardian websites or apps. No one is licensed to use them anywhere else.

All fonts are the property of Schwartzco, Inc., t/a Commercial Type (https://commercialtype.com/), and may not be reproduced without permission.

## Useage

### CDN

All of the files in [`fonts/web`](fonts/web) are available from `https://assets.guim.co.uk/static/frontend/fonts/`, e.g.

```shell
https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Bold.woff2
```

### Recommended `@font-face` rules

You should use the `noalts-not-hinted` version of a font unless you really cannot. It provides the best balance between features and file size, and is highly likely to already be in your user's cache.

<details>
  <summary>Guardian Headline</summary>

```css
@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Light.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Light.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Light.ttf')
			format('truetype');
	font-weight: 300;
	font-style: normal;
	font-display: swap;
}
@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-LightItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-LightItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-LightItalic.ttf')
			format('truetype');
	font-weight: 300;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Regular.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Regular.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Regular.ttf')
			format('truetype');
	font-weight: 400;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-RegularItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-RegularItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-RegularItalic.ttf')
			format('truetype');
	font-weight: 400;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Medium.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Medium.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Medium.ttf')
			format('truetype');
	font-weight: 500;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-MediumItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-MediumItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-MediumItalic.ttf')
			format('truetype');
	font-weight: 500;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Semibold.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Semibold.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Semibold.ttf')
			format('truetype');
	font-weight: 600;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-SemiboldItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-SemiboldItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-SemiboldItalic.ttf')
			format('truetype');
	font-weight: 600;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Bold.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Bold.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Bold.ttf')
			format('truetype');
	font-weight: 700;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-BoldItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-BoldItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-BoldItalic.ttf')
			format('truetype');
	font-weight: 700;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Black.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Black.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-Black.ttf')
			format('truetype');
	font-weight: 900;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GH Guardian Headline';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-BlackItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-BlackItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-headline/noalts-not-hinted/GHGuardianHeadline-BlackItalic.ttf')
			format('truetype');
	font-weight: 900;
	font-style: italic;
	font-display: swap;
}
```
</details>

<details>
  <summary>Guardian Text Sans</summary>

```css
@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Regular.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Regular.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Regular.ttf')
			format('truetype');
	font-weight: 400;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-RegularItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-RegularItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-RegularItalic.ttf')
			format('truetype');
	font-weight: 400;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Medium.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Medium.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Medium.ttf')
			format('truetype');
	font-weight: 500;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-MediumItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-MediumItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-MediumItalic.ttf')
			format('truetype');
	font-weight: 500;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Bold.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Bold.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Bold.ttf')
			format('truetype');
	font-weight: 700;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-BoldItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-BoldItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-BoldItalic.ttf')
			format('truetype');
	font-weight: 700;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Black.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Black.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-Black.ttf')
			format('truetype');
	font-weight: 900;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextSans';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-BlackItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-BlackItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textsans/noalts-not-hinted/GuardianTextSans-BlackItalic.ttf')
			format('truetype');
	font-weight: 900;
	font-style: italic;
	font-display: swap;
}
```
</details>

<details>
  <summary>Guardian Text Egyptian</summary>

```css
@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Regular.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Regular.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Regular.ttf')
			format('truetype');
	font-weight: 400;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-RegularItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-RegularItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-RegularItalic.ttf')
			format('truetype');
	font-weight: 400;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Medium.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Medium.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Medium.ttf')
			format('truetype');
	font-weight: 500;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-MediumItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-MediumItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-MediumItalic.ttf')
			format('truetype');
	font-weight: 500;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Bold.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Bold.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Bold.ttf')
			format('truetype');
	font-weight: 700;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-BoldItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-BoldItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-BoldItalic.ttf')
			format('truetype');
	font-weight: 700;
	font-style: italic;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Black.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Black.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-Black.ttf')
			format('truetype');
	font-weight: 900;
	font-style: normal;
	font-display: swap;
}

@font-face {
	font-family: 'GuardianTextEgyptian';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-BlackItalic.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-BlackItalic.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-textegyptian/noalts-not-hinted/GuardianTextEgyptian-BlackItalic.ttf')
			format('truetype');
	font-weight: 900;
	font-style: italic;
	font-display: swap;
}
```
</details>

<details>
  <summary>Guardian Titlepiece</summary>

```css
@font-face {
	font-family: 'GT Guardian Titlepiece';
	src: url('https://assets.guim.co.uk/static/frontend/fonts/guardian-titlepiece/noalts-not-hinted/GTGuardianTitlepiece-Bold.woff2')
			format('woff2'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-titlepiece/noalts-not-hinted/GTGuardianTitlepiece-Bold.woff')
			format('woff'),
		url('https://assets.guim.co.uk/static/frontend/fonts/guardian-titlepiece/noalts-not-hinted/GTGuardianTitlepiece-Bold.ttf')
			format('truetype');
	font-weight: 700;
	font-style: normal;
	font-display: swap;
}
```
</details>

## Deployment

All of the files in [`fonts/web`](fonts/web) are continuously deployed on a successful build of the main branch.

## Caching

The cache control value for the font files is set to `max-age=315360000` (10 years).
