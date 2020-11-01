# Desjardin Test App

## Setup

- Install Node.js (if you don't have it installed)
- Clone the repo
- Open terminal in the "Sample-01" directory
- Run "npm install && npm start" (run the 2 commands separately if you're using PowerShell)
- open "http://localhost:4200" in a browser.


## Choose a code snippet that you find interesting and describe in a few words why you chose it

```typescript
  loginWithRedirect() {
    this.auth.loginWithRedirect();
  }
```

I found this piece of code the most interesting.
It is a single line of code that replaces days of work.
It would take me days to accomplish the same thing with Spring Security, BCrypt, MySQL, and implement third-party authentication services.
I like the fact that you do not have to worry about patching security vulnerabilities and keeping the code up to date since everything is handled for you by auth0. This is my first experience working with Angular and auth0, it was a pleasure working with them.