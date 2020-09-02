# CRA with Redux

## Why?

The better question is, "Why not?"

It can become quite cumbersome on different projects to set up the exact same structure that you end up using time and time again. I was using some automation I set up with bash, but figured what better way to really customize CRA than with my own template, especially considering that the Facebook team set up CRA to enable using your own templates. Now is as good a time as ever to start building up my own templates for different projects, and in a way that might help others in the future.

## What's included?

This template sets up the React application with a components directory that has both a bootstrap Navbar and Footer, a containers directory that already sets up the store configuration within a provider component and is wrapped with withRouter and connect (though connect is set to null props for both state and dispatch to props), while also implementing React Router and default Landing and NotFound components, and the regular App component. This template very specifically is set up using Redux through a separate store directory which houses the store's actions for creator + dispatcher files and reducers where the rootReducer is already initialized and set to pass up to the store's core. This makes adding more reducers a synch. Beyond that, there's an empty images directory (for now) where images will be available for whatever purpose rather than free-floating in the tree.

## Updates?

Yes, I'm planning on updating this template with more updates as the original CRA tool gets updated. I'll have a script set up soon that will check at least once per day for these updates so that I can go hands free and keep working on other potential templates since this isn't the only template I'll need and that I'm sure others will need either. If I get more people forking or cloning from this project, than I'll consider more templates in the future, but for now, I'll work on maintaining just this one.
