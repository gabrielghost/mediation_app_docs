# Project Mediation App

This project is based on a need for streamlining the divorce or separation process. This is the development diary of the process.

## Day 1 - 5th February 2018

To recap what I've worked on up until this point - On Saturday I was working through a logo idea - we have two names in contention - 1. SplitPea and 2. MediateMe. 1 has a more aesthetic concept, and 2 has more of a ring to it.

On satruday I roughly sketched out the splash page for the application, initially as SplitPea. Yesterday I thought that perhaps it might work well by using the same aesthetic as SplitPea, but instead of 'peas' there are still emojis, they are just blue instead. Below are the two options:

![Splitpea](./assets/split-pea-logo.png)

![MediateMe](./assets/mediate-me-logo.png)

I'm torn! I like the green, but I like the ring of the MediateMe too. Both circular critters are cute and I think give the brand a more playful child-like edge which is essentially the purpose of this project - to keep the children in mind.

The two splash pages are as follows:

![Splitpea](./assets/split-pea-splash-1.png)

![MediateMe](./assets/mediate-me-splash-1.png)

### Today's Objective

Now there's a basic aesthetic going, whichever one is chosen, I think clarity on the user journey as far as wireframes is the best place to start. At the moment they might not look like much - just text on a page, but the entirety of the app should be plotted out. Once this is done, and know how each page feeds into the other, we can start to fill each page in with designs and see how the flow works on a deeper level. This may take a few days to work though, but this is today's aim. I'll plot this out visually using sketch, so that if I get taken by a particular passage of thinking, it won't take too much to fill it out with more details.

If I get bored of the process thinking, I might design some little blue critters this evening.

#### The thinking

So I think I'll start with the mediator wireframes, simply because without the mediator, at least initially, there will be no partners, and that's how they will be invited into the system. For this we need:

- Mediator login page
- Case CRUD
- User CRUD

So I've worked through the login pages, and the case indexes. See below. 

![MediateMe](./assets/mediate-me-case-index.png)

I'm now thinking about how best to display the case data to the mediator.


## Day 2 - 6th February 2018

Today I'm going to focus on the user show page - at the moment we're still looking at everything from the view of the mediator, as that will need the most funtionality - for users we can just hide things where appropriate. Probably I'll lay out all of the information for now, only to review later. The aim of today is to complete all of the mediator account views, and hopefully move onto the user account views by this evening. Image below is the progress of the client profile page from yesterday.

![MediateMe](./assets/mediate-me-user-show.png)

![Client profile](./assets/client-profile.png)

## Day 3 - 7th February 2018

Today I extended the case profile, and dug deeper in to the finances:

![Case profile](./assets/case-profile.png)

![Client profile](./assets/client-profile-details.png)

![Client profile](./assets/client-profile-income.png)

![Client profile](./assets/client-profile-income-2.png)

## Day 4 - 8th February 2018

Today I'm going to review the progress thus far and decide on design decisions that I've made, or need to make. It's a review of the short sprint that has been made. I'll also speak to the client to see how they are feeling about the designs so far.

The main 'to do' items at the moment are as follows:

- a way of representing when a client hasn't filled in the referral form, and perhaps a progress bar attached to that
- mediators should be able to edit any of the entries? perhaps, though the edit should be logged
- deciding where the attachements should be placed is an important point, and will be decided based on what additional information needs to go alongside them - probably quite detailed instructions about what is needed will be required here
- be good to establish how the 'split' process works, so we can best mimic that - probably with something like a wizard?
- is the best way of displaying all of the information in a list with expandable areas, like it is at present, or should the screen be split into two - with main headers on the left, and figures on the right? Only issue with this is when migrating to mobile or tablet this might be harder, though could possibly make use of the hierarchical menu (similar to the iPod from yesteryear....)