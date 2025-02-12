Transcript
So go to zero one.

Select coffee beans.

Say zero five.

Go to basic data one purchasing.

And then accounting.

The plant is Chicago one.

I say coffee beans.

Dark roast Arabica.

The unit of measure is pound material group is 015.

Enter purchasing group.

Any purchasing group is fine.

And in accounting select a valuation class of.

3000 because it's raw material.

And the price control is we because it's a moving average and in valuation category.

Specify now that we have defined the types and categories.

And we have to specify for plants which categories are allowed.

For example, for Chicago plant, I am allowing the category country of origin to be used in the material

master for split valuation.

For that, go to local definitions.

And then you'll have to specify your plant.

If it is not there, you'll have to do a page down or page up.

So select Chicago one.

And go click on this button.

And you see that this automatic batch is active.

We want country of origin.

Go activate that right.

And you can just keep it or you can deactivate it.

I don't care.

Okay.

For a plant, you can have multiple categories active, right?

You could be evaluating materials based on country of origin or you could be evaluating materials based

on grades, so on and so forth.

And now that we have activated that valuation category, country of origin for the plant, save it.

Now go back.

And let's create coffee beans as a material.

M01.

And let's create a new coffee beans.

Okay.

0506.

Whatever.

Right.

Not zero one.

Hit enter.

Select basic view purchasing and accounting for now.

And select Chicago one.

And we're going to say coffee beans, dark roast Arabica.

Yeah, that's fine.

And pounds.

Material Group 015.

Uh, any purchasing group is fine and in the accounting view.

Go to valuation category, and if you select the dropdown, you should have your valuation category,

their valuation category description Country of origin.

So this is how you associate the categories that you have created with the plan.

Now, this might sound a little complicated, but what we are trying to say is create all these different

categories based on which we want to do split valuation.

And assign that to the plant.

That's it.

When you do that, any time you create a material for that plant.

You have the option, you don't have to do it.

You have the option to select that particular characteristic.

In this case, country of origin.

In SAP.

It's called category.

In general.

And if you go talk to business, they might call it characteristic or something else.

So go select country of origin.

Okay.

And select Evaluation class 3000.

That's for raw materials.

Right.

And then select moving average.

This always has to be moving average, otherwise the whole purpose is lost.

And yes, I want to save it.

Now.

Creation of the material Master doesn't end here.

You have assigned it a value.

All right.

Now, if you go try and create a goods receipt or purchase order or anything of that sort for this material,

the system does not recognize the different characteristics that we have assigned to that material.

In order to do that, you have to create the material again.

Plant and storage location data and accounting data.

This time when you click okay, it will ask you for a plant.

For a storage location.

Of course, coffee, because we have selected storage location data and it will also ask you for valuation

type.

Okay.

And this is where you say now create a view for this material for value India.

You see, this is what I meant by complication.

So don't always just go for these characteristics, create them and ask the business to use it.

It creates complications.

So always ensure that there is a very good reason why they want to do split valuation.

All right.

So select India.

And then all you have to do is click.

Okay.

Click okay.

And then the accounting data.

Select 3000 as usual and moving average price.

We?

Enter.

You want to exit?

I want to save and exit.

Yes.

Then.

Also go and create this material for.

Other storage locations and other characteristic values.

Same as before Chicago one coffee bean storage location and the valuation type this time.

Let's select Colombia or Brazil.

So X says that this is already maintained.

Now we're going to maintain for Brazil.

Select the valuation class 3000.

And.

The price control is we enter.

Oops.

3000.

Now look at this valuation class 3000.

Not allowed for valuation type Brazil.

So for raw materials, the valuation class is always 3000, right?

But since you have given a valuation category, you have to always ensure that against Brazil we have

created an account reference.

So there's something wrong in the configuration we have done.

So go escape.

So get away from this material.

Go back to configuration.

IMG.

Middle management.

Valuation and account assignment.

Split valuation.

Configure Split valuation.

And go to global types.

Select Brazil.

And you see, it doesn't have an account reference here, right?

So that's the reason why you are not able to associate this characteristic to the material coffee beans.

We were able to do it for India, but not for Brazil.

So go select Brazil.

Click Change and Account category Reference zero one.

That's for raw materials.

Right.

Go.

Click.

Save changes for Saved.

Good.

Go back all the way and let's start creating that material.

Zero one.

Coffee Beans oh five.

And general data and accounting data.

Plant storage location.

And Brazil.

Now let's put a valuation class of 3000.

And call this as moving average.

This time it works.

Right.

So every time you create a new characteristic value, always associate an accounting reference.

And don't worry about an accounting reference at this point until we get to account, determination

will not be able to understand account reference.

All right.

So we have created this material, the same material, Coffee Beans zero five.

With the characteristic country of origin for two different values or types.

Brazil.

India.

Now, what's the whole purpose of doing this?

This is to ensure that we can maintain valuation at.

The country of origin level.

So I am procuring so much of goods and I have so much of stock of Brazilian origin.

And I have so much of stock or so much of goods of Indian origin.

So let's see that in action.


