<h1 align="center">
<img width="40" valign="bottom" src="https://icon-library.com/images/project-icon-png/project-icon-png-8.jpg">
Pelorio Architecture Guide
</h1>
<h5 align="center">A structure guide for building big applications for optimal team experience.</h5>
<h5 align="center"> (Assume Refactoring friendly and multiple code blocks that might or might not be connected) </h5>

## Folder Structure

```
assets/
docs/
scripts/
app-main/
|  └── app-api-gateway/
|           └── Internal
|           └── External
|           └── Plugins
|  └── app-modules/
|           └── account-modules/
|                      └── S1 (Specialization per domain)
|                      └── S2
|                      └── S3
|           └── analytics-modules/
|                      └── S1
|                      └── S2
|                      └── S3   
|           └── limiter-modules/
|                      └── S1
|                      └── S2
|                      └── S3
|  └── app-ui/
|         └── app-auth/
|                └── S1
|                     └── signin/
|                     └── signup/
|                            └── SSO
|                            └── facebook-sso/
|                            └── google-sso/
|                            └── github-sso/
|                └── S2
|                └── S3
|         └── app-dashboard/
|         └── app-analytics/
|
|  └── app-android/
|  └── app-ios/  

```
