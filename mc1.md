# Mini Challenge 1
## Phase One
Phase one for the blog project involves making it *fully functional*, in other words,
making it so that all views are accessible through links and ensuring that all the functionality
is working as expected up until this point.
### Acceptance Criteria
1. Generate a home page.
2. Generate an about page.
3. Ensure the "new" functionality works (this refers to our PostCreateView).
3.1. We already have a view and a url pattern for it, we just need the template.
4. Add anchor tags (links) to your navbar and other templates as required to ensure all views are accessible through the browser.
5. Test
### Note
Steps 1 and 2 are conducted by ensuring we have all necessary:
1. Views
2. Urlpatterns
3. Templates
4. Configurations (see config/settings.py)
Remember: It is not cheating to check the previous project, all mini challenges are open book.

# Mini Challenge 2
## Overriding templates
### Acceptance Criteria
1. Override the template for password_change, ensuring that it matches the rest of your site.
1.1. template_name = "registration/password_change_form.html"
2. Override the template for password_change_done, ensuring that it matches the rest of your site.
2.1. template_name = "registration/password_change_done.html"
3. Test, ensuring that it is possible to set a new password with the modified forms.
4. Add a link somewhere on your site, that allows users to access this feature (password_change).