---
id: login
title: Login
slug: /sdkstools/cli/login
---

Authenticate on the Tigris instance

### Synopsis

Performs authentication flow on the Tigris instance

- Run "tigris login [url]",
- It opens a login page in the browser
- Enter organization name in the prompt. Click "Continue" button.
- On the new page click "Continue with Google" or "Continue with Github",
  depending on which OIDC provider you prefer.
- You will be asked for you Google or Github password,
  if are not already signed in to the account
- You'll see "Successfully authenticated" on success
- You can now return to the terminal and start using the CLI

```
tigris login {url} [flags]
```

### Examples

```

# Login to the hosted platform
tigris login api.preview.tigrisdata.cloud

# Point all subsequent commands to locally running instance
tigris login dev

```

### Options

```
  -h, --help   help for login
```

### SEE ALSO

- [tigris](tigris.md) - tigris is a command line interface of Tigris data platform
