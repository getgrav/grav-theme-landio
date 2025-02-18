# v1.5.0
## 02/18/2025

1. [](#improved)
    * Migrated all `http://` references to `https://` to fix mixed content warnings
    * Removed Unused JS and also social counts as those API calls are no longer available in 2025

# v1.4.1
## 01/15/2021

1. [](#improved)
    * Fixed autoescaping in preparation for Grav 1.7

# v1.4.0
## 03/21/2019

1. [](#new)
    * Set Dependency of Grav 1.5.10+ which has support for new **Deferred Block** Twig extension
    * Implement assets rendering using **Deferred Block** Twig extension 
    
# v1.3.0
## 01/24/2017

1. [](#bugfix)
    * Update header.html.twig. Makes requests protocol independent, so no more errors that the social content is loaded over an insecure network

# v1.2.0
## 09/09/2016

1. [](#bugfix)
    * Drop the form twig overrides as they break the forms, and don't really customise the output. Update forms for the newest Form plugin markup

# v1.1.0
## 07/14/2016

1. [](#improved)
    * Fixed login form language strings
    * Center form in medium screen size
1. [](#bugfix)
    * Drop requiring Admin to enable frontend login
    * Removed randomization of testimonials
    * Fix language in html tag
    * Delete unused composer.json
    * Remove unneeded streams from Theme YAML
    * Fix trailing letter in the pricing modular
    * Add form nonce to the form template

# v1.0.0
## 11/10/2015

1. [](#new)
    * ChangeLog started...
