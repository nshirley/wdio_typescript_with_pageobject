# WIP

---

## Overview

This is an example of how to use a pacakged webdriverio pagobject library. This is a sister project to [wdio_pageobject](https://github.com/nshirley/wdio_pageobject) and built using the default example test provided by [webdriverio](https://webdriver.io/) when setting up from their CLI tooling.

---

## Usage

### Local Development

As stated above, this is designed to work in tandem with the sister project [wdio_pageobject](https://github.com/nshirley/wdio_pageobject). As such, you'll want to clone both this and that project locally.

Steps:

- Follow steps in sister proejct [wdio_pageobject](https://github.com/nshirley/wdio_pageobject) to create local yarn link.
- Back in this repository, run

```
yarn link "wdio_pageobject"
```

- From there you can import any of the PageObjects like so

```TS
import { SecurePage } from "wdio_pageobject"
```

#### Building Tests:

All tests should live in the `/test/specs` folder. Add a new spec and pull in the appropriate page objects that you need.

#### Running Tests:

```sh
yarn test
# yep, that's it
```
