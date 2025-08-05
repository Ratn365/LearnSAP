 
Transcript
So we want to accept vendor 4003 but reject the other two vendors.

How do we do that?

Go to m49 the price comparison.

Put the collective number in there.

Hit.

Execute.

And we said we want to accept the first vendor, the vendor that was ranked first but reject the vendor

two and vendor three.

Right.

Select that line item.

The one that you want to reject and click on quotation.

Select Rejection indicator.

See.

Same thing with the vendor that has ranked the third.

Select it, go to quotation reject indicator save.

That means that the first vendor is selected.

The second and third are rejected.

So now we have to send the messages to the vendor saying, Hey, you know what?

You have been rejected.

Go to print.

Transmit.

Put the numbers in there.

What are the numbers?

Uh, six, seven.

If you don't know those numbers, that's fine too.

You can just go click on the possible list of values and go by the collective number 2001 and hit enter.

And it automatically picks up all the purchasing documents, the RFQs that we have created against that

particular collective number.

Click Okay.

Click okay.

Now we only need to send the rejection letter to two of these vendors.

So select them and click output message.

And if you want to see them, you just go click on display message.

You can you can see that it's a rejection letter and it's related to the particular RFC.

When it was dated, what were the materials that we asked for?

ET cetera.

ET cetera.

Now we can also send an acceptance letter to the first vendor.

Right.

And how do we do that?

So instead of abs in the message type.

Abcc is a rejection letter quotation rejection, right?

There is also a quotation acceptance output and instead of a BSR, which is a quotation rejection,

you could have any EU, which is the message that you send when you create the quotation.

Or you can create your own custom success bidding message which SAP standard does not have and use that

message to print the corresponding output.

For a successful bid.

Now, this is not the message for a successful bid.

It it's a message that goes out when you issue the RFQ.

But standard does not have the successful message output.

And in order to have that, you have to create your own custom message.

Now, outputs and messages is something that we have not seen yet.

We'll see that in customizing in one of the later chapters.

But for now, just understand that it's going to be a message type here.

You select a successful quotation message type as opposed to rejection and select that RFC number or

quotation number and execute.

Select that quotation number and click on output message.

So this should send the accepted or successfully accepted message to the vendor.

4003.

So this completes the RFQ and quotation process.

So what have we done here?

We have asked for 100 kilos from these three vendors and asked them to submit a quotation.

We have done that through the RFQ.

Step number one, and we have tagged all these RFQs with a collective number called 2001.

And after some time, step number two, the vendors have responded and we have recorded their terms

like prices, what payment terms they're ready to offer when they can deliver the goods by so on and

so forth.

Step number three is we did a price comparison.

We did a price comparison between the different quotations that we received.

An SAP helped us finalize which vendor offered the lowest price.

And all the higher prices were rejected.

We sent them rejection letters and the successful bidder.

Was accepted and we sent him an acceptance letter.

So we have successfully completed the quotation process.

Now what do we do?


