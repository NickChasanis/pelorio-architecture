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
| └── about/
| └── assets/
| └── design/
| └── guides/
|       └── guides.md
|       └── dev-guides.md
|       └── prod-guides.md
|       └── readme.md
| └── project/
| └── spec/
scripts/
app-main/
|  └── app-api-gateway/
|           └── Internal
|           └── External
|           └── Plugins
|  └── app-modules/
|           └── account-modules/
|                      └── S1 (Service Specialization per domain)
|                           └── Datastore
|                           └── Filter logic
|                           └── 
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

<h5 align="center"> It starts as a modular monolith with expansion in mind and easy refactoring, the idea behind this structure is that you start big but you can also split per module and UI, so most features will need two folders for the code to not only be testable but also runtime tested since you only need the basic configs for either frontend & backend  </h5>