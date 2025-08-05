 
Transcript
And in order to do that, what we have to do is first check for the stock.

Okay.

Be.

What?

The stock of coffee beans.

Oh, one in the coffee storage location.

It's hundred.

Okay, so in Chicago there is 130, but in coffee bean storage location, there's just 100.

Okay, let's only focus on that particular storage location.

So the book inventory.

Is hundred in Chicago.

One coffee storage location.

Now, we have already created a physical inventory document.

Let's go see.

Okay.

And what are the settings?

We want to put it as freeze book inventory.

Right.

Control s.

Oh, by the way, there is a setting that has to be done.

I forgot about that.

Freezing of book inventory in storage location is not allowed.

So there is an SP setting that specifically says that you can freeze book inventory in a particular

storage location.

This just ensures that that process of freezing book inventory is not allowed in all storage locations

because it's a sensitive process, right?

You have to keep a separate lot or place where you can store this ad hoc goods, receipts and goods

issues.

So the warehouse has to be prepared for that.

Not all warehouses are prepared for it.

Unless they are trained to go to SPRO, IMG, material management and inventory management and physical

inventory.

Go to physical inventory.

And allow freezing of book inventory balance and storage location.

So select your plant.

Click.

Okay.

And in coffee bean storage location you are allowing.

The blocking of book inventory.

Save the transport.

And we are ready.

To mark that physical inventory document as.

Relevant for book inventory.

Freezing, Right.

Save it now.

It's not giving that error anymore.

So there is 100 in book inventory, right?

We just want to simulate that scenario that we have seen.

There is 100 in book inventory now.

We've create a physical inventory document.

And marked it as freeze.

Book inventory.

That means the book inventory from this point on until you close that physical inventory document is

going to be 100.

Right now.

Let's do a physical inventory counting.

Say it's 3 p.m..

Say the process started at 10 a.m..

And now it's 3 p.m..

Right.

And.

Let's say the price of physical inventory counting is happening, but suddenly we have done a goods

receipt.

Okay, so my go.

Some coffee has come in.

All right.

We'll just do it against the cost center.

That way we don't need a purchase order, and we're going to do a quantity of 25.

And this is A201

and plant Chicago one and the coffee beans storage location.

All right.

And that's against the admin cost centre.

So the admin department suddenly needed £25 of coffee.

Right.

Item.

Okay.

Check if everything is okay because we have marked that physical inventory document as posting of book

inventory system will not throw an error.

Now.

What does me say?

100 quantity of coffee beans.

After this is posted?

It should be 125, right?

Is it 125?

Let's go and check m m be execute.

Make sure that the storage location is also selected.

So the book inventory.

Has gone up by 25 to 125.

But I said that book inventory does not change.

That's the whole point, right?

We are freezing the book inventory, but when we do a goods receipt, it's increasing the book inventory.

Why?

Because the freezing of book inventory is happening specifically for the purpose of physical inventory.

So for the purpose of physical inventory, it's still 100.

Let me tell you why.

Now, the stock is 125, right?

Now let's do a physical inventory posting.

Of 80, assume we only found 80.

Now the difference should be 20.

Right?

But if the book inventory were 125.

If this 25 was added to the book inventory here, it would result in a difference of 45.

And that's not what the system does.

So let me show you how.

So we have created a physical inventory document and we enter the count.

So it's not 100, but it's 80.

Okay, Save it.

Now post the differences.

Enter.

What's the difference?

You see?

20 It's not 45.

So when you freeze the book inventory in.

You can see the correct count if any GR happens, but for the purpose of physical inventory, SAP treats

it as 100.

It froze the inventory only for the purpose of that physical document.

Everybody else in that company can see the increase or decrease in stock.

But for the purpose of that physical inventory, it's 100.

No matter how many goods you receive or how many goods you send out, it's always 100.

And now I'd say.

£0.05 pm.

You count the inventory and mark it as 80 and at 6 p.m..

You post the differences of 20?

Right.

20 is the difference and 80 is the new physical inventory stock.

So you are confirming that there is not 100 but 80 in stock.

And now 25 has been added here.

Right.

Now, after you post the difference, what should be the stock?

Is it 80 or 80 plus 25 or 125?

It's 80 plus.

Any other additions or subtractions that have happened?

80 plus in this case, 25.

That should be 105.

So let's post this document.

A difference of 20.

Save it.

Now immediately after that if you go to.

Execute the total should be 105.

Right.

It's the actual inventory that you have counted plus.

Any other additions or subtractions.

Gucci use or goods receipts that have happened subsequent to 10 a.m. when you started the count and

froze the inventory.

This is called freezing of the book inventory.

So these are the two major constraints that you can impose when you're doing physical inventory counting.

One is posting block, the second is freezing of the book inventory.

You know what a posting block does.

And you also know what freezing of the book inventory does.

So that concludes physical inventory.


