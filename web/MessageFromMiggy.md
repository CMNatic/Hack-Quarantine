This is Next.js, a React web framework

You will be building the static assets of this app for viewing in the nodejs app that Ben built out for us.

# How to determine what endpoint goes where?
You have two endpoints. A development one, and a production one. You can figure out how to use environment
variables to determine which one you hit at what point

# Caution
Make sure not to use any of the functions for "Server-side rendering"
They won't work in production as all of your app will be built into the public folder and served that way through express