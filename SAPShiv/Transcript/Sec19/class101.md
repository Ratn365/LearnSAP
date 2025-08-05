 
Transcript
So we have seen what is transfer posting.

We have seen stock types.

We are going to see one more example of transfer posting in this chapter.

This is our Chicago plant.

And then we have seen examples of.

How to move stock between storage locations.

We have seen the one step method in which we can do the stock transfer, and we have also seen the two

step way in which you remove the stock.

And then.

Place it in stock.

And until that point, it's going to stay in a transit location.

So this is to step.

This is between storage locations.

Now, is the process any different?

If you were to transfer stock between two different plants, why would you want to do that?

Well, just like the way we transferred material from one storage location to another, we could very

well transfer goods or stock between one plant and another.

In Chicago, we could have multiple plants assuming each plant is a store.

You could have multiple stores and you could transfer stock between one store and the other.

That's one example.

It's not always the case that one shop or one store needs to be a plant.

2 or 3 different stores that are adjacent to each other could be served by a single plant.

Or entire Chicago with, say, ten shops, ten coffee stores could be handled behind the scenes with

a single plant.

How it's arranged will depend on how we are doing business.

For example, if I were doing the franchisee model.

Like Dunkin Donuts.

Each store would be a plant.

If I were owning the stores, ten stores and all of them say or geographically located, very close

by.

In that case, why would I want to have an overhead of ten different plants?

It's much simpler if I service all of them behind the scenes with one plant, one set of storage locations.

Or maybe a couple and the shops will just act as a front for sales.

Remember, a plant is where you own and stock the goods.

Oregon manufactured goods in cases where you don't need manufacturing.

If you outsource everything.

Still, you need a plan.

And still.

Why do you need a plant?

Because a plant is the location at which you do valuation of stock.

We're going to get more into valuation in one of the next set of chapters.

For now, let's just say that I've opened a new plant in San Francisco.

So this is Chicago.

And this is San Francisco.

Now, do I need to have a plant in San Francisco?

Let's say you own just two shops, okay?

One in Chicago, one in San Francisco.

In this case, do I have to have two different plants, one in Chicago and one in San Francisco?

Again, the answer depends on the way I run my business.

I don't always need to have two different plants.

Say, for example, purely from a logistics perspective, if it makes sense that I can transport the

goods from Chicago to San Francisco, like coffee or whatever.

Then I don't need a separate plant in San Francisco.

Anything that I can manufacture here, I use it here.

Anything that I can send over to San Francisco, I could send over to San Francisco like coffee beans

or anything that doesn't perish soon.

And pastry and bakery items like muffins, cakes.

If sending them over to San Francisco in a truck makes them stale, I could procure them locally from

another vendor, in which case I don't need a plant in San Francisco.

Well, that's one way of doing business.

Another way, Say, for example, the way I do my pastry or bakery item is one of the reasons why the

coffee shop is such a big hit.

In which case I want to manufacture my own items.

And I can't transfer them from Chicago to San Francisco because things are going to go stale, in which

case I would definitely want to set up a plant in San Francisco where I manufacture my own pastry items.

You see, you can go either way.

What we want to see in this chapter is how do I transfer goods from one plant to another?

Can I do it using simple transfer posting?

Yes.

Again, there are two ways of doing it.

The easiest way is, of course, to do a one step.

Transfer posting to do the stock transfer again.

I'm using the word transfer posting and stock transfer sometimes interchangeably and sometimes not.

Right.

The reason being transfer posting is more of an SAP oriented term.

I don't think transfer posting is used anywhere outside of SAP.

A more commonly used business term is stock transfer.

The business would understand stock transfer much better.

But transfer posting is a very specific term, but transfer posting refers to a much more broader range

of activities.

Stock transfer is a very specific, narrow range of activities.

A stock transfer is the process of transferring the goods from a storage location to a storage location

or from a plant to a plant.

That's it.

That is stock transfer.

A transfer posting, on the other hand.

Can do so many things.

What you might ask me say, for example.

Ten kilos of coffee went stale.

What do you do?

You throw it away.

So you junk £10 of coffee.

Let's not stock transfer.

Isn't it?

That's scrapping £10 of coffee.

The process is called scrapping.

You use transfer postings for that.

So what's happening here?

You're changing the value of the goods.

There is no physical movement, so it's not really transfer of stock.

We'll see some more examples of transfer postings when we go to some of the next chapters.

For now, what we are going to do is do a stock transfer using transfer posting.

Well, is there other ways to do stock transfer?

Yes.

And we're going to see that in the next chapter.

For now, we are going to do the stock transfer, which is basically a process of moving stock from

one location to another between plant to plant storage, location to storage location.

ET cetera.

ET cetera.

Using the method of transfer posting.

So to do a transfer posting from one plant to another, what is the movement type that should be used?

That's the first question you have, isn't it?

I don't know.

Let's go search.

But before I do that, I have to create the San Francisco plant.

Right.

So let me go do that.

SPRO, IMG.

And you know the drill.

Enterprise structure.

Definition.

Logistics, General.

Define copy.

Check.

Plant.

Executed and copy delete check planned.

And say you want to copy from the plan that you already created.

Say Chicago one.

It's easy that way, right?

You got all the settings done for Chicago.

You can just copy those settings.

It's going to take a couple of seconds.

And the source plant is Chicago one.

And the target plant that we want to create is San Francisco, right?

I'm going to say SFO one and click okay.

Okay.

It's going to give a number of warnings.

Just click.

Okay.

The first warning is about transport number ranges.

Well, we haven't seen number ranges yet, so don't worry, we are going to cover number ranges in detail

in one of the next set of chapters or courses.

For now, just say okay.

And behind the scenes it's going to actually copy a whole bunch of settings for you.

And then the TR or transport request is being created.

And then finally you get the message which says plant Chicago copied to SFO.

Cool.

Say okay.

And you're done.

Now there are some additional steps like assigning the plant to company code, assigning the plant to

purchase.

Things like that.

Now, some of these things might automatically be done for you behind the scenes because you did a copy.

You did not create the plant from scratch.

You copied it from Chicago.

SAP might automatically have done that for you.

Now, why am I not being sure about it?

Why am I not saying SAP has done it for you?

Because some of the settings might not have been copied.

Now, which settings are copied and which settings are not copied?

It's not something you don't need to worry about.

Don't waste your time on that.

Instead, what I would recommend is go check.

If some of the major settings are done already and then execute some transactions.

Executing a transaction is a surefire way for you to understand and know that.

Your configuration is working.

It's like building a rocket.

Well, that might be an extreme case.

Just but just to give you a feel, you could you could build anything you want, but unless you test

it, you not be sure.

Right.

And executing a transaction is a way for you to test what you have configured.

And before I go execute it, let me go and check the assignment for one quick thing.

What do you want to do?

I want to make sure that the plant is assigned to the company code.

Where do you do that?

You do that in logistics.

General of assignment.

So I go to assignment Logistics.

General assign plant to company code.

Execute and click on position.

The plant is SFO.

One enter.

I don't see an entry there, so let's go create.

One so new entries.

Us zero one.

Uh, San Francisco.

Oops.

It says that the entry already exists.

Why is that?

Well, sometimes this search, the search in the configuration doesn't work as expected.

Because this is not a search, but instead it's it's going by position now.

Don't trust this completely.

More a better way to search it is by going to selection and clicking on by contents.

And here you can say plant.

Click okay.

And plant equals San Francisco one and click Choose.

There you go.

So going by selection contents is a more accurate way to search for any of your configuration results.

So this relation is already there.

So US zero one is already assigned to San Francisco plant.

So it's already done for you.

You don't have to do anything.

Maybe some other settings are required, but we don't know that yet.

So let's do a transfer posting, which is a way of testing what we are wanted to do and then see if

it really works.

So go to my go.

And we are trying to do a transfer posting between Chicago and San Francisco.

So transfer posting other.

That's what we choose.

And what is the default movement type here?

It's been set to 301.

Now it's not always set to 301.

It could be set to any other movement type.

We have to make sure that we are choosing the right movement.

Type 3 or 1 in this case happens to be the right movement type.

I know that from the description.

I see their transfer plant to plant, and I don't know that number either.

I don't know off the top of my head that 301.

Is the movement type for transfer posting from plant to plant.

I don't know that and I don't need to know it.

I can just go here, look at the possible list of options and the description of it will clearly say

what that movement type does for me.

In this case, 301 does transfer posting plant to plant, and it also says it's one step.

Cool.

That's what we want, right?

So select that and.

The material say is coffee beans.

If you have been keenly observing the whole process, you might have a question here.

I'll let you think.

But for now, we'll specify the plant and material.

So the source plant, the from plant is Chicago because we want to transfer goods from Chicago and the

storage location say is coffee.

Okay.

And the target is San Francisco.

Okay.

Any light bulbs go off.

Not.

That's fine.

And the storage location is coffee.

Does it work or no?

Let's hit.

Enter.

Seems okay.

And what's the quantity?

£100, assuming £100 exist in the Chicago storage location, let's say.

Check.

It says posting only possible in periods 2016, blah blah, blah.

Now we know how to fix this, right?

Go to MMP.

Enter the company code US zero one.

Enter today's date.

Hit.

Enter.

And hit.

Execute.

Okay.

Period.

Closing is complete.

Now let's try it again.

Check.

You see what I was talking about?

Material not maintained in plant.

San Francisco.

What does that tell you?


