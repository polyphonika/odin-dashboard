### Findings from creating the dashboard project

Understanding grid, particularly with how rows and their heights work, was important.

I encountered an issue where images were full size. This was because, by default, they are their intrinsic height.
You need to constrain them or explicitly set the height. If you have a parent div with height 100% (or explicit size), you can set 
your image to be 100% and it will be 100% of the parent This only works if the parent size is set. If not, it will be full size again.

I also encountered issues around using Grid for the small elements, say buttons in the nav bar. I would prefer flex for those.
It was a steep learning curve but one I'm happy to have made.