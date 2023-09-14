<h1 align="center">
<img width="40" valign="bottom" src="https://icon-library.com/images/project-icon-png/project-icon-png-8.jpg">
Pelorio Architecture Guide
</h1>
<h5 align="center">A guide for building big applications for teams.</h5>


## Folder Structure

```
assets/
docs/
scripts/
app-main/
|  └── app-api-gateway/
|  └── app-modules/
|           └── account-modules/
|           └── analytics-modules/   
|           └── limiter-modules/
|  └── app-ui/
|         └── app-auth/
|                └── signin/
|                └── signup/
|                └── SSO
|                     └── facebook-sso/
|                     └── google-sso/
|                     └── github-sso/
|         └── app-dashboard/
|
|
|
|  └── app-android/
|  └── app-ios/
|  

```