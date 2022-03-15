HELLO WORLD 


This was easily our most productive week!  We were able to create and deploy a test version of our 1033 Program news app using Flask and github pages.  

From the outset, our intention was to improve upon the example set by project1033.org, an app with a lot of potential, but some confusing UX choices.  We felt that their app didn’t do a good enough job of telling the full story of 1033.  While it might be a valuable resource for readers curious only about what their local police departments have received via the 1033 program, it is less than ideal for readers looking to learn more about 1033 or to gauge its impact in the aggregate.  

While we are both very proud of our first attempt at remedying some of the Project 1033’s issues, we’ve run into some of the same ones and there is yet work to be done in turning this into the app that we initially envisioned.  

We first sought to address the issue of visualizing aggregate impact.  Our solution to this was our map and summary table housed on our index page.  We wanted to give the readers an idea of which departments in Maryland have made the most use of the 1033 program.  While we didn’t completely do away with the idea of giving readers a look at each individual 1033 transaction, we felt it was more important to lead with the big picture.  

Our week started with geocoding our data to place police departments accurately on our map.  This was actually a pretty easy process thanks to Awesome Table.  Our final product is a Datawrapper map with points denoting police departments and sized according to the combined value of all items they have received through 1033. 

While it isn’t perfect (we would prefer that each point also linked to the department’s detail page), we feel that our map is one of the greatest successes of our project.  With minimal context, a reader can understand what the icons represent and start to draw conclusions for themselves.  

Next up, we’re planning to expand the snapshot of data that we included. We have plans to dispatch a ton of public information to local police departments requests to see what, if any, deaths happened as a result of a each weapon acquired through the 1033 program. We also have plans to continue refining the text and to add some more guidance on how to use the page. 

We would also like to enhance our detail pages to nail down the right code for the button (we know it should be <a href='../index.html'><button>Go back to see all</button></a>) but GitHub Pages and Flask were giving us a bit of trouble. We also want to continue to build some templating out to include some figures on each department on each detail page. 
