### Backlog:
-  code-coverage - line to fix up: `spec/page_spec.rb:91`
-  Fix `page_element_interaction_steps.rb`: Triple Expectations and non-Helper expectation
-  Fix `page_section_steps.rb` - Triple expectations
-  Generic Features are sometimes hard to understand. Look to rework the Gherkin
-  `page_element_interaction_steps.rb:49` Shouldn't be there as its performing Actions
-  `site_prism/addressable_url_matcher.rb` - Needs more of a spring clean
-  `SitePrism::Page#wait_until_displayed` - Re-call existing method and re-raise
-  Begin to refactor `displayed?(*args)`, to remove enumerable args (Shouldn't be enumerable)
-  New feature `SitePrism::Section#native` returning `root_element.native` To help with
people wanting to access the base native object (Honouring what maintainers said)
-  Exceptions Spec needs writing
-  element/s spec need a slight rename / tidy
-  Release 2.11 to Rubygems
-  Update of Ruby Version to supported version
-  Generic Update of dependencies (Unrestrict everything we don't care about)
-  Rubocop LineLength reduction (Continue this, will be hard work, probably several PR's)
-  Rubocop MethodLength reduction (Should be a small-er PR)
-  Begin to start using let blocks across specs (Dev points update)
-  Add developmental guidelines / setup information
-  Review iFrame specs, add/amend where appropriate
-  Allow scoping iframes to then be passed into element native object
- `.gitignore` review RE different development environments - Needs Mac/Windows/Other dev input
- Generic suite wide linting in `/lib` need to wrap method arguments up (Remove space separations)
- Generic spec walkthrough - (have done setions_spec.rb - which might need renaming)

### To monitor (Assumed fixed elsewhere)
-  Capybara compatibility around iFrames - Now should be more compatible. Remove once 2.12 is released
