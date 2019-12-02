# CreateSACLLoginWindow

Script to lock the loginwindow to one AD User

The MacOS login window can be locked down to an AD User or group if the Mac is bound to AD. This script will challenge the user to confirm either the currently loggedin user or another user to apply the control to. Subsequent to this we can also add an AD group whereby a member of that group is also able to authenticate to the MacOS login Window.

Any previous user will be removed from the SACL on the login window. Local Admins can continue to authenticate.

Updated November 2019 on MacOS 10.14
