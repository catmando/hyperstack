# Welcome to Hyperstack!

**Hyperstack 1.0 and Hyperstack 2.0 are work-in-progress. Please consider everything in this repo as ALPHA.**

Hyperloop (version 0.9) is stable, and the existing website remains in place. If you are looking for a production ready project, then please stay there until this is released. http://ruby-hyperloop.org

In this project, there are two Hyperstack implementations (HS1 and HS2). The goals of each are detailed below.

This website loads all content dynamically from the HS1 and HS2 projects. You can switch the document base using the link in topbar.  

## Hyperstack 1.0 (HS1)

### Release goals:

+ Solidify current Hyperloop DSLs, Public APIs, documentation and tutorials.
+ Close any major issues, especially those that will potentially break or add significantly to DSLs or Public APIs.
+ Provide an easy migration path from Hyperloop to Hyperstack
+ Separate out client code from server code, i.e. client code will end up in a single NPM module, server code will end up in a single rails gem.  
+ Use convention over configuration, and provide as simple as an install process as possible, as simple as adding a gem and an NPM module.
+ Brand new website completely built with Hyperstack technology
+ CI/CD build and deploy process for all NPM modules, Gems and the Website project

### Change management needed:

+ Explain the Hyperloop rename / mostly done
+ Launch new website / mostly done
+ Update docs, setup and tutorials

### Out of scope / constraints:

+ No DSL or API changes, installation changes are fine, but Hyperloop 0.9 DSL code must just-work with HS1
+ Any functional changes/bug fixes made in this codebase must serve as a reference in the HS2 codebase (a merge is unlikely)
+ HS1 will be replaced with HS2 when HS2 is stable and in production on some commercial sites
