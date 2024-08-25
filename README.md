# About

Hi everyone, this is my github page for personal projects that I work with in my downtime.
A lot of what I know about coding has come from a mix of a bootcamp and working closely
with mentors across my career, and I am grateful for their continued belief in me and
their willinginess to feed my curiosity.

### Languages, current
* Python, proficient
* SQL, proficient

### Languages I'd Like to Learn
* Rust
* Javascript

# Coding Projects
### A standard method for calling the FreeStyle Libre 3 API
If you have an FSL 3 you can share your CGM data with another user using something called
the Libre LinkUp. Basically, on some time delay (I think it's 15 minutes), your CGM can
pass data through this API to another user for monitoring, with a 5 minute resolution.

Abbot does not publish documentation for this API, so open data enthusiasts have
casually been probing the application and API for a while, trying to figure out
a way to get it to work. There are lots of good documents, but no standardized method
that is deployable or shareable, so I started one to deploy in Docker to push data
into a local database.

This project still needs a lot of work, but for what it's worth it works fine.

### A solar consumption simulator
My husband wants us to buy batteries for our solar system with the caveat that we
buy enough battery to get through an outage of no less than four consecutive days.

I built a simulation method which takes in net consumption in KwH, a set of 
batteries, and then estimates the total probability that a setup will successfully
get through an arbitrary `n` number of days.

### A method for building glucose tolerance curves
Once you have data from your CGM, you should be able to use it to help make informed
decisions about your healthcare - especially with the help of your providers. As monitors
get more ubiquitous (as they will soon be available without a prescription), diabetics
and people worried about diabetes need reporting tools to have informed discussions
with their providers.

The reporting software that you can access online is great, but there's no given
method for using the data to answer:  what typically happens at mealtime? Using data from a CGM,
you can use this tool to describe how your body typically responds to your current diet
and medication.
