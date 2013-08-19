---
layout: post
title:  "OmniAuth Avvo"
date:   2013-08-14 16:12:32
tags:   omniauth-strategy ruby
category: project
---

[Avvo.com][avvo] strategy for [OmniAuth][omniauth]

## Usage

in your `omniauth.rb`:

```
  provider :avvo, YOUR_APP_ID, YOUR_APP_SECRET
```

Your `request.env['omniauth.auth']` hash will contain:

* `name` - friendly name
* `email` - your login email address
* `permissions` - array of granted permissions on Avvo.com

See [OmniAuth docs][omniauthsetup] for more information on integrating with a standard OmniAuth strategy.

## Obtaining an API Key

Contact [Josh King][josh] to get set up.

[avvo]: http://www.avvo.com
[omniauth]: https://github.com/intridea/omniauth
[omniauthsetup]: https://github.com/intridea/omniauth#integrating-omniauth-into-your-application
[josh]: mailto:josh@avvo.com