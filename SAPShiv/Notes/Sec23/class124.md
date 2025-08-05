 
Transcript
Now, there are a couple of elements of configuration in Sbarro for reservations.

Let's go look at that Sbarro.

IMG.

Go to material management.

Inventory management.

Reservations.

And default values.

Go select your plant.

In this case at Chicago.

Click on position.

Type in Chicago.

And this is for Chicago.

By default, movement is always allowed.

Right.

So like I said, if you want to not allow movements beyond a certain date, check this off.

But by default, it's always checked on.

And this is days until which the movement.

Can be started.

Meaning in cases like this where the delivery needs to be done 30 days from now.

If the movement is checked off.

It's not until ten days, meaning on, let's say 20th of January is when you can start doing the goods

movement.

So it's the number of days within which, if there is a delivery, movement, automatically is enabled.

Now that's a setting that's not required all the time.

But if you want to do it, you can go set it.

The second thing is retention.

Say, for example, I have reserved £100 of coffee on Jan first.

And I required for Jan second.

But I totally forgot about it.

Right.

So the warehouse manager tomorrow on Jan second went and kept my £100 of coffee ready.

I did not turn up.

I forgot.

I went on with my business.

And Jan 30th came.

Jan 31st came and February 1st came.

Maybe the warehouse manager has kept that coffee somewhere in a corner.

Thinking that I'll come.

But 30 days has passed.

And did not come to pick up my coffee.

In which case, what the warehouse manager has to do is put that coffee back into the lot.

And what happens to that reservation?

That reservation will be cancelled.

The number of days beyond which reservations can be automatically cancelled is this retention period.

So beyond 30 days, reservations will automatically stand cancelled.

Now.

Who can do this?

Automatic cancellation.

Do you have to go manually do it?

No.

There is a reservation management program.

Let me show you that program to you.

Go to logistics again, material management, inventory management reservation and M BVR administer.

So this administers or manages reservation.

This is a program that can be run either in the background or manually.

So what this does is it manages these reservations based on the dates.

For example, if there are reservations that need to be deleted, it can go delete those reservations.

Or if there are reservations for which goods movement needs to be enabled because it has come within

ten days or five days of that time, it can enable that.

So these are the two functions that can be performed.

And that is done using these two indicators delete set deletion indicator and set goods movements to

allowed.

So any time you run this, if you don't see the results, that's because it's a test run.

You have to go disable this and run using the execute button.

Okay, let's put this on and execute.

So these are all the activities that SAP is going to do.

You don't have to do anything.

You just have to click save.

That's it.

Now, if you click save and go back, nothing will happen because it's a test run.

If you delete the test run.

Okay.

And hit.

Execute.

These are all the reservations.

See their way back from 2003 2002.

They'll all be removed.

That all be deleted?

Right.

So changes have been made.

Now, that was not something that you have seen previously because it was run in test mode.

Now you've removed the test mode and all these reservations are deleted.

Now, if you go back and execute this again.

You not get them?

The list is gone.

They're all deleted because they're pretty old.

Now, if you want to really test it, you can go create a reservation, right?

This reservation is for today.

Let's say coffee beans.

Oh one quantity 114.

Again, a weird number just to show that, you know, this is really the reservation that we are working

on.

Save it.

66919 is created.

Now.

If you go to administer And.

Run this for today.

You will not get anything.

But if you run this for something that is 30 days from now, which is a simulation, right.

So if you run this for, say, 12th December, not oh one, let's say oh five, because that's clearly

30 days beyond today's date.

You'll see that.

6918.

Right.

Now that's a simulation.

You don't have to really do it.

But if you run this management program so far into the future, it's going to be deleted.

That's what it says.

Now it's a test run.

Nothing is going to be deleted.

But if you run it so far into the future, really, that reservation will be deleted.

So this is basically a program that's used to.

Purge reservations that are not really necessary.

30 days old reservations are purged.

And if the goods movement indicator is not set, they can be set automatically.

And as usual, you can use a variety of criteria like cost center order, asset network sales order

to pick specific reservations that you want to manage.

If you don't want to manage all the reservations at one go, you can just specifically choose all the

reservations made against the HR Cost Center or the admin cost center or a particular project.

So that's called managing reservations.


