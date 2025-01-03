# abc
Action plan

Update Gems
Ticket Name: Update and Replace Gems for Rails 8 Compatibility 
Description:
Remove unsupported or deprecated gems from the Gemfile.
Replace outdated gems with modern equivalents:
Replace restful-authentication with devise.
Replace will_paginate with kaminari.
Add webpacker for asset management.
Ensure mysql2 is included as the database adapter.
Run bundle install and verify dependencies. 
Acceptance Criteria:
Gemfile contains only Rails 8-compatible gems.
All gems successfully installed with bundle install.



Migrate Authentication
Ticket Name: Replace Authentication System with Devise 
Description:
Remove authenticated_system.rb and authenticated_test_helper.rb.
Add Devise to the project.
Configure Devise routes and callbacks.
Update authentication logic in controllers and views. 

Acceptance Criteria:
Devise integrated and working.
Authentication logic migrated to Devise.
