 
And then there is numbering external, which in this case is.

41.

What does that do?

It allows the user to enter their own number range.

And right next to the internal number range, we have an external number range.

Z4 is our internal number range something that we have created and you can also have an external number

range.

What's an external number?

Range.

Purchase order Number.

Will be created or will be entered by the user.

Like how new do you want to save?

No.

And it's going to be Z01.

Right.

4001.

Some material number.

Which is order number.

And here you can enter an external number.

Can you enter any number you want like that?

Enter.

Oops.

It says document number not within number range.

Now what do we do?

That means you can't enter any number you want.

The user cannot enter any number they want.

It has to be controlled with the document type.

In this case, the number range external is 41.

What is 41?

41 is

41 all the way to 4999.

And the numbering status is blank, meaning nothing has been taken so far.

So do a control C.

Then go there.

Enter something in that number range.

You could start there.

Or you could start with A01, whatever.

Anything within that number range.

Right?

Save.

You see that?

Now you have created a purchase order.

With your own number and it has to be within that number range.

And that number range has to be declared as external.

How is the number range declared as external?

When you create number ranges, you have to declare that number range as external here, right?

And then in the number ranges when you create that number range.

It has to be checked as external.

So if you go to 41.

41 is checked in as external.

And when you do that, SAP asks the user to enter the number instead of auto generating it.

Why do you want to do it?

Why does a business want to create external number ranges?

Think of a scenario like GE or some big heavy engineering company that does like ten orders in a month.

That's it.

They do ten orders in a month.

Think of a big power plant installation scenario, right?

They do some generators or they do some transformers for big power stations, and each of them costs

like 20 million.

Right.

Even one order a week is huge.

In cases like that.

Every month there are ten orders.

And every year there are what?

A total of 120 orders.

Each order is worth a million.

10 million?

20 million.

And they're not just procured just like that.

There is a process.

And that process is very elaborate.

Each order might take one year, six months, nine months.

Two months.

In cases like that, it makes sense to create a purchase order with an external number.

Because you want to easily remember it.

In fact, you don't even want to enter it as numbers 41000.

You would want to enter it as a combination of text and numbers.

Like, for example, if the power plant is creating a purchase order with GE and that is forward, that

is for, say, a turbine.

Okay.

GE Dash two RB dash zero one.

That's the purchase order.

And it is very easy to track, right?

Just by looking at the number, you know that this order is for a GE and this is for a turbine because

there's going to be one line item, just one line item in the case of coffee shop.

It doesn't make much sense.

You know, it's a commodity business in speciality businesses where there is not a huge volume but high

value.

In cases like that, it makes sense to go with external numbers.

You want to remember every purchase order and track it to completion so you can use external number

ranges in those cases.

And then we have field selection.

What is a field selection?

The field selection.

Is a grouping of field selection groups within which we have fields.

Now, if you remember the material type configuration or the vendor account group configuration.

Or even the info records.

Each of them were associated with a field selection group that controls how fields are dictated hidden,

optional, mandatory, so on.

Right.

So you have the screen.

It could be material master vendor, master info record, and now in this case, a purchase order.

Right?

And then there are so many different views, right?

In the case of purchase order, there is a header that has so many different tabs.

Admin data vendor data address data and then at the line item level.

There are so many different line items, right?

The line item level again, there are so many different tabs.

The entire purchase document type is assigned to a bunch of field selection groups.

In this case it is nbrf.

Okay, let's look at what is Nbrf.

Where are these field selections?

Screen layouts.

Define screen layouts.

And what's the.

Selection.

Field selection.

You go to NB, there are so many field selection groups.

So within a field selection, this is called a field selection.

And field selection has so many field selection groups.

Each of these field selection groups compared to the Taps, field selection groups.

Each selection group.

Can be linked to a tab, not just a tab directly, but a grouping of tabs.

Example basic data item at the item level.

Terms of delivery and payment.

This is at the header level.

Administrative data.

This is at the header level.

Right.

So if you go inside each of these, what do you have?

You have required optional display.

That's it.

You don't have a suppress here like how we have in the material master or vendor master or any kind

of master data.

You don't have suppress here.

Now, you might be wondering, you know, there is no check mark in Material Master, for example.

There is no option to do both a required entry and an optional entry.

Right?

It can either be optional or it can be made required.

Now, can you do that here as both like that.

No, that's not possible.

He hit Enter says select no more than one field.

Right.

It's only possible that you can do either required or optional or display.

Right now, Plant is an optional entry.

In case of a purchase order.

That's what this is.

Terms of delivery and payment.

Currency is a required entry.

That's what this says.

Is it really required?

If you go to a purchase order, try to create one, it will ask you for currency.

It typically defaults from the vendor master, so you wouldn't even know it.

But if not, if it is not there in the vendor, then it will ask you to enter a currency.

This screen layouts are pretty complicated.

There are so many of them here, right?

Akita, Akita, Akita.

And then there is this.

And then there is that.

So many different things.

What do you do with these things?

You know, how do you even customize them?

Now, if you go back to the document type.

And go to this guy.

Right.

Let's pull everything real close.

This field selection group here and for Framework Order, it says F-off.

And for stock transfer, it says Ubf.

And for regular NB, it says NBF.

Right.

So what does these things do?

Now, in order to understand this, we have to understand a little bit about how SAP opens up that purchase

order.

In a May 21st.

When it looks at the standard purchase order.

So when m e 21 n.

Purchase order transaction is entered.

There is a program behind the scenes.

When that program runs, apart from many things that it does, it looks at these field selection groups.

This is not the only field selection group.

NBF is not the only field selection group.

This is the primary field selection group.

On top of that, if you go back.

Go to screen layout.

There are so many different field selection groups.

One that starts with a.

This is called.

Activity.

Let me put that here.

Field selection groups.

1RAKTA for display H for change.

We for create, right?

So let me put it as act.

Start.

This is based on the activity.

What are you trying to do?

Are you trying to create a purchase order?

Display a purchase order?

Change a purchase order?

Well, you might argue.

The transaction will dictate it.

Right?

Yes, it will.

And that's why we have this as well.

For example, M 21 n.

Right.

So you have m e 21 star, right?

Or two star.

This is the transaction.

And then we have the RT.

Three is t star.

This is the item category.

And then.

We have.

Up Subitem That's not really relevant in our case, right?

And then these are the pricing screens.

So what's the point?

Don't get too overwhelmed.

This the point being at each of these level, we can have field selection groups.

The same set of fields can either be set, for example, payment term.

There is a configuration for payment term in activity as either display or.

Mandatory or optional the same payment term.

It can be set to either display or mandatory or optional.

In this screen and this screen.

Why?

The reason is SAP tries to give you as much flexibility as you want as your business needs in terms

of allowing certain items to be mandatory or optional based on the item category, based on the document

type, based on the transaction.

Let me give you an example.

You have created your own document, Type ZI01.

In this case during create.

For subcontracting.

You don't need payment.

But you need payment term during regular or standard.

How do you do that?

In the zero one field group you set payment term.

To.

Optional.

During create he set it to optional.

Right.

But at the item category level, you set the payment term.

To let's say, if it is mandatory.

Mandatory.

And then SAP does an intersection of all these different field selection groups, meaning if it is optional

here, optional here and mandatory here, then that field becomes mandatory in that particular scenario

only when it is Z01 during create transaction and the item category is subcontracting L.

In that case, only that field will be made mandatory, but for regular, maybe during another transaction

like display or change or maybe during different document type, it's not mandatory.

Right now.

You don't have to use this functionality.

This is a little complicated.

You don't have to use this.

It causes confusion.

It's available.

And if you want to use it, you can use it.

If not, you don't have to use it.