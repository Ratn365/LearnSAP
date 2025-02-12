 
Transcript
So in this section all along, we've been learning about returns.

So we have talked about two different kinds of returns.

Standard returns, which are called return delivery.

And there is another type of return called return per.

And we know how to create either of these.

Now after we return goods, say with Amazon.

We get a credit, right?

We either get a money or we get a credit note.

A credit note is as good as money because we can buy goods with a credit note.

Now, this is all good.

We return goods, we get money.

But what happens if there is an issue in pricing that purchase order?

Meaning.

Say the price of a purchase order is dollar 1000.

100 kilos.

Of coffee.

At.

$10 per kilo then.

You receive the goods.

For a quantity of 100.

And then you do an invoice receipt.

For, say, $1,000 at at $10 per kilo.

This is all good.

But later what we have realized is maybe the vendor has overcharged us.

Or the vendor could have also undercharged us.

The price should have been, say, $11 instead of $10.

What do you do now?

So the price we have found out is not $10, but it's $11.

In which case the vendor has undercharged us by a dollar.

So we need to give the vendor how much.

So at a rate of $11, this is going to be 1100.

Right.

So we need to return $100.

To the vendor.

This is a case of undercharging and in case of overcharging, say it should have been Dollar nine.

But the vendor has charged us $10, in which case.

We have paid the vendor $1,000, but we should only have paid 900.

And we should have received or we should receive a credit of $100.

So in case of overcharging.

The vendor overcharging us?

We receive a credit.

In case of undercharging.

We receive.

The debit note.

A debit note is a notice to pay more.

A credit note says, Hey, you know what?

I need to pay you.

Right.

It's pretty logical.

If the vendor over charges you, you get a credit.

If vendor under charges, you you have to pay the money back.

So again, let's start here.

We'll create a PO.

We'll do a goods receipt.

We'll do an invoice receipt real quick, and then we'll do either of these scenarios.

First, we'll do the undercharge and then we'll do the overcharge.

So real quick, let's create the purchase order for a quantity of 100.

Right now, we have become experts in creating purchase orders, returns and invoices.

Right.

So the price of $10.

Save.

Pick up the PO.

Michael Goods movement.

Enter the purchase order number.

You're going to receive it into our coffee storage location.

Item.

Okay.

And quantity of 100.

Save.

Enter an invoice.

Put today's date in there.

Enter the number and select invoice over here.

So this is important.

If you select a credit memo, you won't get the right amounts and the amount is $1,000.

Everything cool?

Save it.

So we have created this, right?

So it doesn't take long.

Really.

It takes like, you know, three minutes to do these steps.

Now we're going to create.

So we will do this scenario now where the vendor has undercharged us.

So instead of 11, which is the right price, he has charged us $10.

So we need to give back $100.

So how do you do that?

So we know the number.

Go to my row and instead of invoice or credit memo, select subsequent debit.

All right.

Put today's date in there.

And enter the number.

So the quantity is 100 and the amount is 100.

Okay.

We are giving back $100 to the vendor.

When you give back to the vendor.

It's called a debit memo.

When you get money from the vendor, it's called a credit memo.

Right.

So subsequent debit is something that you do when there is no logistics involved here.

There is no logistics, right?

We are not returning the goods.

We are not taking in the goods.

It's a pure financial transaction.

Now, you might have a question.

Why do we select a quantity of 100?

Because we are not doing a logistics transaction, right?

So why do we select 100?

Well, that hundred is used for tracking.

So somewhere down the line, if somebody wants to know what is the amount that you are giving this credit

for?

Just by looking at the debit memo, people will know that this.

Is the quantity against which we are giving a debit.

Of $100.

Right.

So quantity ties things together and that's why we have a quantity there, although there is no logistics.

The truck does not come.

Pick up the goods.

Nothing like that.

It's a pure financial transaction, but we still have the quantity there to tie things together from

an accounting perspective.

All right.

So save it.

And that's it.

Now all debit memos are typically blocked for payment.

That's how SAP configures it by default.

You can go release that document.

By double clicking it.

Go back.

Go to logistics.

Material management.

Logistics, invoice verification, further processing and release Blocked invoice.

Put your invoice number in there.

Hit, execute and select it and click release.

And don't forget to save it.

This document is released because we have to give money back to the vendor, right.

Just so that nobody misuses it.

By default, those kinds of documents go on a block.

This just ensures that there is a little bit of oversight in terms of giving money back to the vendor.

Right.

Now we can also create a credit note.

It's called as a subsequent credit instead of a subsequent debit.

So it's a case of we undercharging the vendor.

So the vendor says, hey, you know what?

The price is not $10, it's $9.

I've accidentally charged you $10.

So I'm going to give you back a credit of $100.

We are very happy to take it right.

The way to take it is with a subsequent credit.

Put your number in there.

The quantity of 100 comes up and how much does the vendor needs to give us back a quantity of 100.

So put that in the amount here.

And click save.

That's it.

Now, if you go back to the purchase order, run as usual to the purchase order history, you'll see

all these transactions tied together to that purchase order.

First there was a goods receipt of 100, so we've asked for a hundred kilos of coffee and that has been

delivered.

And then the vendor sent us an invoice for 100.

So thousand dollars is being paid to the vendor.

And after that we have realized that the vendor has undercharged us.

So we created what's called as a subsequent debit.

So you can just click on this document if you want to see the corresponding debits and credits.

This is a credit for $100 and this is a debit for $100.

A debit is marked as an invoice and a credit is marked as a credit memo.

And these are all subsequent debits and credits log.

So we got the goods receipt log here, we got the invoice receipt log here, and then we got the logs

for subsequent credits and debits.

So that's how you do subsequent credits.

So this is called a subsequent.

Debit.

Debit is where we need to pay the vendor and this is subsequent.

Credit.

Credit is where the vendor needs to pay us.

Now, this is nothing to do with returns.

Remember, you also get a credit memo when you do returns.

Right.

But this is not a return.

There is no logistics involved.

There is no goods movement involved.

It's a pure financial transaction where this credit memo is got because the vendor has overcharged us.

Right.

We have got this debit memo from the vendor because the vendor has undercharged us.

Now let's let's summarize all the subsequent transactions that we have done with respect to the original

P2P transactions.

So what have we done?

We started with a.

Right.

And that was for a quantity of 100.

Right.

And the amount.

Is.

Thousand.

100 into ten.

Right.

Then we have created a goods receipt again for a quantity of 100, and the amount is 1000.

Invoice receipt for a quantity of 100 amount.

$1,000.

So this is the primary P2P transaction, right?

Now, after that, we have done a number of steps.

The first step is one of the steps is we could create a return delivery.

So with respect to the goods receipt, we could do a return.

Delivery.

Right.

And we could also create a credit memo.

So you do this step when you want to do returns.

Right.

When you want to do returns, you do a return delivery and do a credit memo.

Now, if the vendor has overcharged us, then what do we do?

Then we don't have returns.

We don't have any goods movement.

What we do is against this PO.

We just create.

An invoice receipt.

That's called as a subsequent.

Credit.

Which is the case where the vendor is paying us money because he has overcharged it.

All right.

Now, what if the vendor has undercharged us?

In which case.

So we need to pay the vendor.

In that case.

Instead of creating.

A subsequent credit you create.

A subsequent.

Debit.

Right.

So we have covered subsequent credits, subsequent debits and returns.

Now, another type of returns that we have covered is called a return or return.

PIO.

What is the return PIO?

A return PIO is a PIO.

You don't need to reference anything.

Like the newspapers transaction.

At the end of the week, we are going to create a new PO.

And the difference here is we are going to mark that item at the line item level as a return item.

And we try to do a goods receipt.

It doesn't do a goods receipt instead does a goods issue.

So if the quantity is for 100, we're going to return a quantity of 100 and you're not going to create

a standard invoice.

Instead, you're going to create a credit memo.

So we receive amount for that.

100 quantity.

So we have talked about for subsequent cycles to the standard cycle.

So this is the standard cycle.

All right.

This is called returns.

This is called Returns Po.

This is subsequent credit.

Or credit memo, and this is subsequent debit.

Right.

So to the standard P2P cycle, we have created four different subsequent steps.

Returns.

Returns.

P0 Subsequent Credit.

Subsequent debit.

This concludes the Returns chapter.

So in the returns chapter, we have also seen not just returns but credits and debit memos.


