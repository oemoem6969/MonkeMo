# Monke Mod Manager not official

<a class="d-inline-flex flex-items-center flex-nowrap Link--secondary no-underline text-small mr-3" href="https://github.com/The-Graze/MonkeModManager" data-ga-click="Repository, language stats search click, location:repo overview">
          <svg style="color:#e34c26;" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-dot-fill mr-2">
    <path d="M8 4a4 4 0 1 1 0 8 4 4 0 0 1 0-8Z"></path>
</svg>
          <span>Here is the official one</span>


This program will install custom mods into Gorilla Tag automatically, and can be re-run in order to update the mods

This uses the github api to get the latest release of all these mods, so you know you'll always be getting the latest version!
(If you've made a mod that you want added to the installer, send me a message on Discord! `the.graze`)

| Version | Supported          |
| ------- | ------------------ |
| 6.0.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :x:                |
| -4.0    | :x:                |

## To have your modded added
DM me:
* The Github repository of the mod you want added 
* Any dependencies
Mod submission is likely subject to change in the future.
### Ensure that
* your mod is built in the monke mod manager compatible format through `MakeRelease.ps1` (replace `netstandard2.0` with `netstandard2.1` in the code) or you use a DLL in your release
* you list the correct dependencies
* your mod is fully working
