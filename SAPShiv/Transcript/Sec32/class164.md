 
he next parameter is purchasing.

Value.

Key.

This is a field that you see in the purchasing view of the material master.

If you go to the purchasing view, enter the plant, say Chicago one.

You'll see a purchasing value key.

So what does this represent?

This represents.

A grouping of all these different values, the reminders.

The delivery date variance under delivery and over delivery tolerance.

Minimum delivery quantity in percentage.

All of them put together can be grouped into one number called the Purchasing Value Key.

Why?

Because SAP bi material master design does not allow you to specify these values explicitly, meaning

you can't go and just put ten or 20 or 30 here.

Right?

I can't change it.

It's all grayed out.

I'm trying to change it.

I cannot change it.

The way to do that is by going here and changing the value from two to, let's say, something else.

Say you want the third reminder or the first reminder to be five days.

Choose this.

But by choosing that, you are also changing the rest of the fields.

Right.

So it's a grouping of some of the purchasing fields like reminders and delivery tolerances with just

one parameter.

And how do you configure it?

Well, just go to F one.

Okay.

Hit F1 on that field and select this button.

Customizing and say continue without specifying project.

The reason why I'm doing that is because I don't know where the customization for this is.

It's out there somewhere.

It's there in material Master purchasing material Master.

Define purchase value Keys.

If I don't know the path, you could use that to find out where exactly in Sbarro.

You can go configure it.

It's not available for all fields or all areas of customization, but wherever it's available, you

can use it.

That's the easiest way to find out where exactly you can do this customization.

Now go to purchase value keys.

And you could create a new entries, copy an existing entry.

Right.

And then say call it Z1, and then you could set any number of days you like.

You could customize it any way you want.

First remainder.

Second remainder, of course.

Second remainder has got to be bigger than the first and delivery tolerances.

This is say, 10% and this is over.

Delivery is 10%.

Right.

And then that's it.

The number of entries copied.

Z1.

Save that as a transport and that's it.

Right now go back and you can change it from two to a Z1, which will have the values that you have

created yourself.

Right.

That's a purchase value key.

So this is number six and number seven.

Is plant specific.

Material status.

This is very similar to cross plan material status.

It's the same field, except it's plant specific.

Where do you set it?

If you go to the SP1 view, do you have one view?

You don't have 101.

Coffee beans or one.

Let's see if we can create an view.

Yes, we can go to one.

Select Chicago, one plant.

There you have the plant specific material status.

What does this do?

So it has the exact same functionality as a cross plant material status in the basic data.

Instead, it only applies to one plant.

Right.

You see, it has the same parameters blocked for purchasing block for casting, blah, blah, blah.

So when you put something here, typically this is used for production.

So if you want to stop producing coffee beans or something in one plant, say the Chicago plant.

You could use that.

It's producing.

Remember, it's not purchasing.

Or you could also do a procurement ban on one particular plant.

Yes, definitely possible.

All right.

This is plant specific material status.

But that about finishes discussion on most of the major fields in the material master from a functional

perspective.

But that doesn't mean that these are the only fields in the material Master.

You should know.

There are so many other fields, but when we discuss those other fields, they have another story to

themselves.

For example, if I want to discuss type, I can discuss that in isolation.

It has a little background to it and you know, it has to be discussed as part of a separate chapter.

Think like auto group.

These are all things that need a separate discussion.

So I'm not doing that as part of this chapter or this set of chapters in Material Master.

So whenever they are relevant, I'll discuss the corresponding business process and discuss about those

fields.

Some of them have already been discussed and some of them can be discussed as we go forward with the

rest of the chapters.

So the next chapter is material type customization.