﻿# [DEPRECATED] Version Command (choco version)

**NOTE:** Version has been deprecated and will be removed in version 1.0.0. 

 If you are attempting to get local installed items, use 
 `choco list -lo`. 

 If you want to know what has available upgrades, use 
 `choco upgrade <pkg|all> -whatif` or [[`choco outdated`|Commandsoutdated]].

## Options and Switches

**NOTE:** Options and switches apply to all items passed, so if you are
 running a command like install that allows installing multiple
 packages, and you use `--version=1.0.0`, it is going to look for and
 try to install version 1.0.0 of every package passed. So please split
 out multiple package calls when wanting to pass specific options.

Includes [[default options/switches|CommandsReference#default-options-and-switches]] (included below for completeness).

~~~

 -?, --help, -h
     Prints out the help menu.

 -d, --debug
     Debug - Run in Debug Mode.

 -v, --verbose
     Verbose - See verbose messaging.

     --acceptlicense, --accept-license
     AcceptLicense - Accept license dialogs automatically.

 -y, --yes, --confirm
     Confirm all prompts - Chooses affirmative answer instead of prompting. 
       Implies --accept-license

 -f, --force
     Force - force the behavior

     --noop, --whatif, --what-if
     NoOp - Don't actually do anything.

 -r, --limitoutput, --limit-output
     LimitOutput - Limit the output to essential information

     --execution-timeout=VALUE
     CommandExecutionTimeoutSeconds - Override the default execution timeout 
       in the configuration of 2700 seconds.

 -c, --cache, --cachelocation, --cache-location=VALUE
     CacheLocation - Location for download cache, defaults to %TEMP% or value 
       in chocolatey.config file.

     --allowunofficial, --allow-unofficial, --allowunofficialbuild, --allow-unofficial-build
     AllowUnofficialBuild - When not using the official build you must set 
       this flag for choco to continue.

     --failstderr, --failonstderr, --fail-on-stderr, --fail-on-standard-error, --fail-on-error-output
     FailOnStandardError - Fail on standard error output (stderr), typically 
       received when running external commands during install providers. This 
       overrides the feature failOnStandardError.

     --use-system-powershell
     UseSystemPowerShell - Execute PowerShell using an external process 
       instead of the built-in PowerShell host. Available in 0.9.10+.

 -s, --source=VALUE
     Source - The source to find the package(s) to install. Special sources 
       include: ruby, webpi, cygwin, windowsfeatures, and python. Defaults to 
       default feeds.

     --lo, --localonly
     LocalOnly - Only search against local machine items.

     --pre, --prerelease
     Prerelease - Include Prereleases? Defaults to false.

~~~

[[Command Reference|CommandsReference]]


***NOTE:*** This documentation has been automatically generated from `choco version -h`. 

