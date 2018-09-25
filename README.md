# Making gmail's html version look better

Firefox user stylesheets for the `mail.google.com` domain.

## To use
First, learn the name of your Firefox profile directory by visiting `about:support` in Firefox and looking for "Profile Folder"

Then:
```
git clone git@github.com:ryanhinkel/htmail.git
cd htmail
mkdir <firefox-profile-directory>/chrome
cp ./userContent.css <firefox-profile-directory>/chrome/userContent.css
```

