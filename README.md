# What is "Testing"?

## Manual Testing

We preview the application in the browser and we test it there. It is super important because we see what our users will see, we want to polish and make sure that this works.

But, testing the app manually is also "error-prone", It is hard to test all possible combinations and scenarios. 

#### For example,
You add an new feature, or change something of an existing feature. you will probably test that change or the new feature, but you're not going to test all the other parts of your application all the time. Therefore, you might change something which breaks some other feature in your app and since you're not testing everything all the time, that breaking change, that bug, might slip through and maybe you eventually catch it later.

That is why we need "Automated Testing".

## Automated Testing

You write extra code that runs and tests your main application code, a standard thing to do in modern development. you write test the individual building blocks of your app, then test all those blocks together.
