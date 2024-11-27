---
layout: page
title: Sensitive and Censor
permalink: /language/reference/versioning/v10/features/feature-4/
exclude: true
---
<br>_FEATURE: Sensitive and Censor_<br>

The censor CLI argument provides a way to cover up some sensitive data. <br>

For example, I might have a personal list that is absolutely fine for my personal use. However, if I need to share it publicly, I might want to edit out some of my private or sensitive information. The censor flag is a convenient way to do just that. The way it works is that users use the {sensitive}, {secret} and {hidden} decorators in their describe source code, and when they need to get a censored output, they use the censor flag. {sensitive} entries will have every character that is not a whitespace replaced with a question mark. {secret} and {hidden} will completely hide the data - {secret} will produce a random number of black squares and {hidden} will produce some random-length gibberish text. This is implemented per translator, and not every translator might support this argument. Currently it is supported only in the inbuilt HTML translators.

<br>
### Links
[Back](/language/reference/versioning/v10/transpiler10/)