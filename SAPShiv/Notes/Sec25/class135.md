 
Transcript
So what is the solution?

The solution.

Is to do physical inventory or inventory counting at least once a year.

For fast moving products, you know, things that go in there double digits or triple digits per month,

you can do it once a month.

Example.

If Samsung is selling 100 TVs per day.

That's a big number.

You might have to do a physical inventory counting once a month because each TV represents a large volume.

Or if a company like Cummins is selling two generators a month, that's not a big number.

You can count it once a year.

Now, if differences exist between physical inventory versus book inventory, do an RCA or root cause

analysis, which is trying to identify what could have been the root cause.

The person sitting in the warehouse typically would understand why this would happen.

Is it because of theft or is it because of other human errors?

So the solution to checking this problem is to do inventory counting and finally do an RCA or root cause

analysis to understand why things could have gone wrong.

Now how to do inventory counting.

In SAP.

The first step to do inventory counting is to generate a physical inventory document.

Well, we have seen purchase order document.

We have seen a goods receipt material document, accounting document.

Similar to that.

There is also a physical inventory document.

We'll see some of these in the system.

And second point is do a physical inventory counting.

Go to the warehouse and physically count that you have £100 of coffee or £1,000 of coffee.

And if you find differences.

Posted differences.

Meaning if there are 100 points of coffee that the system thinks is there in the warehouse, But you

go physically and they find out that there is only £80.

What's the truth here?

Is it 100 or 80?

The truth is, 80 ACP thinks it's 120.

Could be, like I said, lost because somebody has stolen it or somebody has entered the wrong quantity.

Now you go post the difference and say ASAP is not £100 of coffee in the warehouse, it's just 80.

Correct yourself.

That's called posting the differences.

Let me give you some examples.

See, for example, this is our warehouse, the Chicago Coffee Warehouse, or Chicago raw material warehouse.

And coffee is stored.

In a particular lot.

Let's say this is the entire plant.

This is where coffee is stored or coffee of a particular type is stored.

Right.

No, like I said.

Counting of £100 of coffee is really easy.

It's no big deal.

So system things.

That there is £100 of coffee.

So the physical inventory is just £80.

So the difference is 20.

You post it as a difference account and then correct the inventory to 80.

That process is really simple.

But imagine.

That there is £50,000 of coffee.

Well, £50,000 might sound like a lot, but I'll give you some scenarios where £50,000 of coffee is

not abnormal for coffee shops, and physically counting £50,000 is not a joke.

Right?

It will take a day or two days.

So doing physical inventory is a tedious and laborious process.

And that's why.

Typically at the end of the month or at the end of the year, depending on the volume.

People in the warehouse dedicate two days or three days to do this physical inventory.

And during that time, all activities in the warehouse are stopped.

Because you cannot keep counting stock and then keep doing other transactions like goods, receipts

and goods issues.

It causes problems.

Your counting something.

It's like saying you're counting a bag, a bag of beans or marbles.

When you count them.

If somebody pours in some marbles and removes marbles like goods, receipts and goods issues, can you

really keep track of the count of the beans or marbles?

That's not possible.

Right.

And that's the main reason why during that time, all transactions are stopped.

Well, you might argue Amazon doesn't stop transactions.

They go 365 days a year.

Well for that.

There are other special methods and we'll discuss them as well.

So for now, what we're going to do is do these three steps.

Create a physical inventory document.

Do a physical inventory counting.

Post the difference.

How do you do that?

So go to logistics.

Physical inventory.

And physical inventory document.

Go click on Create.

And the plant is Chicago.

So this location is a coffee beans and click okay.

So what do we want to count?

We want to count coffee beans.

The first type of coffee beans.

You know, coffee beans.

Let's say slow roast Arabica.

And we also want to check coffee beans zero five.

You could list as many as you want.

Enter.

And save.

Right.

So this is the document that's created.

Let's just copy the document.

Now you can print this document.

We're just putting that document number in there.

And print it or do a print preview.

Right.

So and this is the sheet that you give out to your employees and say, go count this material.

Go count this material.

And then finally, this dash over here is where they put in the numbers.

So at this point, how much coffee do I have?

I don't know.

I'm not going to tell what he thinks to this employee who is going to count.

I'm just going to give him a blank sheet and say count.

The pounds or whatever units of coffee that's there of this type in this storage location or plant.

So we're going to count coffee beans zero one and coffee beans zero five.

Well, this is an unnecessary line.

In a third line is not necessary.

It's the same material.

So we're going to count zero one and zero five, right?

We're going to go back and delete the third item.

And this sheet is printed given to our employees who work in the warehouse.

And they'll go start counting.

Now let me go to change.

And delete the third item.

I don't need that.

Okay.

It's the same material as line number two.

Okay.

So that's deleted.

Now, what's the second step?

So we have created this document.

So 100001000 some number.

Now, you got to do the physical inventory counting.

So that sheet is being handed over to the employee in the warehouse.

An employee goes to the lot where the coffee is stored and start to do a count.

So he counts the first lot.

The second lot.

The third lot.

Fourth lot.

Accumulates them.

And finally, he thinks that there are £100 of coffee or £1,000 of coffee beans of type one in the storage

location or plant.

How does he enter that in the system?

So he makes a note of that on paper, comes back to SAP.

Enter the material document number.

Enter.

Of course, it's 2016.

And what's the quantity here?

Here the quantity is, let's say £100 of coffee.

This is what is actually present in the warehouse.

There is £100 of coffee beans or one, and there is £200 of coffee beans.

Oh five.

Okay, the third item is deleted, so you cannot really enter anything.

Okay.

Now go ahead and save that physical inventory document.

So what have we done?

We have done a physical counting and entered the counts in the physical inventory document.

Now the third step is to post the differences.

And go to this step.

Post the differences hit enter.

There you go.

What's the difference?

Quantity 745.

And that is a deficiency.

So if you double click that line item.

You'll see that we have entered a physical quantity of 100.

But the SAP has a quantity of 845 in MMP.

So SAP thinks that there are £845 in its stock of coffee beans or one.

But our employees went in and found out that there were only £100.

Now, this could be a mistake.

They might not have counted it, right.

So if there is a huge difference, typically they go and count it again.

Just for that particular material.

Assume it's correct.

Okay.

That means that the difference quantity is 745 minus.

So there is literally a loss of £745.

Now, the system thinks that there are £845, but we only have 100.

So there is a difference of 745.

That's how much is deficient.

And that's the reason why it's shown as negative.

Now, if you look at this material coffee material oh five the book quantity is 100 system thinks that

there is 100.

But physically, when we counted, there were £200.

Okay.

The difference quantity is 100 positive.

That means we have 100 more.

Right.

And you can put some reasons in there.

And the reason why there is 745.

That is unaccounted for.

If you think that it's really true, you can put a reason in there, right?

There might be huge rains.

And coffee got damaged.

Right?

So there's £745 of coffee that got damaged.

So it's going to go into the damage account.

And there is £100 of coffee that you found in excess, right.

For this, you might not need to put any reason.

Right, because it's surplus that was found.

So you don't need to put in reason and.

The system is also evaluating that this is how much of stock that we are writing off.

We are writing off $393 worth of coffee beans or one.

And then second line, we are gaining $1,100 because of £100 of coffee beans or five.

Right.

So what happens to these amounts is what we're going to see after we save this document.

So see.

Oops.

So for object number, range 49 does not exist.

So go to number range 49.

In Fbn1.

Fbn1.

Go to company code zero one.

Go to intervals.

And 49 is what we need to add.

49 for the year 2016.

Let's give a number 5152.

Right.

So we're going to start with, say, five three.

Copy that.

Go.

Here.

Five, three.

99999999.

And click save.

Number ranges are not transportable.

That's fine.

Okay.

There might be other number ranges that are required, but we won't know unless we start posting.

So again, we go back to that document and it pulls up the amounts and just go and click save.

All right.

So the physical inventory document is posted and it created a material document for 9008040.

Copy that document.

The reason why we are copying that is because we want to see how the accounts are being posted to.

How do we see a material document?

M MP zero three.

Right.

It typically pulls up the latest material document anyways and select the material document as 2016.

And what happens here?

There is a 702 minus and a 701 plus one is surplus and one is deficient.

What happens to the accounting document?

Let's see, what are the accounts that are posted to double click on accounting?

And there you go.

Inventory account is 300,000 because our valuation class is 3000.

In the accounting view of the material master.

So that is credited minus you know, with 393 and the losses account inventory losses is debited or

increased by 393.

So this is the amount of material that we lost of coffee beans.

Oh five And that is exactly what is being reflected.

Inventory losses account.

Now in the case of coffee beans oh five.

The inventory is increased by $1,100 and the inventory difference gain account.

See the losses account is 23 3000 and the gain account is 28 3000 and that is credited with $1,100.

This is as expected, right?

The inventory goes down and what goes up?

The losses or the gain account.

So there are special accounts for inventory losses and inventory gains.

And just to balance the inventory that's being lost or gained, you post it to the corresponding losses

or gains account, depending on whether it's a loss or a gain.

This is a very simple way to understand physical inventory and physical inventory counting.

All right.

So we have done these three steps one, two and three.

Right.

Very simple.

Generate a physical inventory document for all the materials you want to count.

You send that employee out to actually do the count.

He enters the count in the system.

And then finally, there are no differences.

There's nothing much you have to do.

If there are differences, you can go and post the differences, and SAP will automatically ensure that

the corresponding accounts are being updated.


