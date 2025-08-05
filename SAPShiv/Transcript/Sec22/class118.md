 
Transcript
Purchase order 4001 with.

Coffee beans, which is a planned item.

So let's go now to a goods receipt.

So go to my go.

Enter your purchase order number.

So the truck has delivered £100 of coffee.

Now you want to add £100 of flour as an ad hoc purchase.

So go to click on non ordered item.

Go to the material tab, enter flour.

And how much do we want?

£100.

Where do you want it?

You want it in the Chicago plant and raw material storage location.

Now, by default, it goes to 501.

Just change this to 101.

And in the partner data who has supplied the material vendor 4001 in the same goods receipt, if another

truck vendor 4002 comes in and you have received the goods there, you can enter a different vendor

here.

But for now let's just enter the same vendor 4001 and click check.

Make sure everything is okay.

Now, what does it say?

Vendor has not been created for purchase.

Aug 3000.

Why does it say purchase?

Aug 3000.

We are working in purchase order US zero one Company code US zero one.

So why does it say purchase?

Org 3000.

This is because for every plant there should be a default purchase order.

And where do you assign that?

You assign that in enterprise structure.

So if you go to enterprise structure assignment, assign standard purchase org to plant.

And select Chicago.

So what is the default purchase order?

3000.

We want you as zero one.

The custom plan that we have created, the custom purchase order that we have created.

Save it.

Now, it's not only sufficient that you do this step, but since you're asking the system to automatically

create a purchase order for a particular material, you also have to make sure that you create an info

record.

Which have created.

So for 4001 Flour purchaser gives zero one Chicago plant have created an info record with $10 in price

and.

The movement type also needs to be configured to automatically create a poll.

How do you configure a movement type?

Well, we have not seen this until now.

The transaction for that is.

Oh, MJ.

Go select your movement type 101.

Hit enter.

And make sure this field, the automatic field, is checked on.

If it's not, it will not create an automatic pool.

When you do the goods receipt.

And the vendor should be marked for automatic.

So if you go to v.

K.

Yum!

Zero three.

Select your vendor and go to the purchasing data.

Hit, enter, enter.

And you see that automatic purchase order.

This should be checked on and.

In the material Master for Flower.

In the purchasing view.

For Chicago plant, of course.

The automatic Poh should be checked on.

So once all these things are in place.

Now let's abandon this because it doesn't work.

Let's go create another goods receipt for.

The purchase order that we have just created.

Now go click Add.

And the material is flour.

Quantity is 100.

And change the movement type to 101.

In planned Chicago storage location, raw material, and the partner is 4001.

Now let's check if everything is okay.

Document is okay.

Save it.

The goods movement.

48 is posted.

Go to zero three.

48.

Hit.

Okay.

And there you see the newly created pool.

This is a pool that was created instantly as a result of this ad hoc goods movement.

Copy that.

Now you can go to M 23 n or 22 n.

Put your purchase order number.

The newly created purchase order number.

And you see the purchase order and you see the price.

What's the price?

$10.

Where was it picked up from?

From the purchase info record that I've created.

So this is how you configure the system to automatically create purchase orders.

So let's summarize the steps that are needed.


