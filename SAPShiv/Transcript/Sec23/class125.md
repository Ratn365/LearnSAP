 
Transcript
So let's summarize what we have learned about reservations.

Reservations or ad hoc requests for goods to be made ready on such and such a date.

Example, I need £100 of coffee on Jan second and today is Jan first.

That is an example of reservation.

I have a customer waiting in line for £100 of coffee.

If you don't create a sales order, you have to do it using a manual reservation.

So a reservation is a request to keep goods ready at a particular point in time.

So it's a request to keep the goods ready.

At a particular point in time for this entity.

Now.

Reservations are typically created manually.

Transaction.

M b 21.

Reservations can be changed.

Of course, using MX 22 like delete items or change quantity change movement type, so on.

Automatic reservations or reservations.

Created from source document.

Our upstream documents.

Example sales orders.

Production orders.

Process orders.

Project orders.

So on and so forth.

And these basically automatically create requirements in MD04.

That's the transaction you can go to view reservations.

So zero four lists all the requirements either from manual reservations or reservations made using source

documents.

And automatic reservations cannot.

Be edited.

Or changed in NB 22.

They can only be changed.

In the source document.

Now in terms of configuration for a reservation.

For a plant, you can specify the number of days beyond which it can be purged.

So the configuration specifies purging or deletion and movement allowed indicator.

If the movement allowed indicator is unset, you cannot do a good issue.

That's not possible.

It has to be set.

Movement allowed tells you or tells SAP that goods can be issued.

If it is not set, that flag is not set.

You cannot do a goods issue.

And it can automatically be enabled when the time comes, let's say five days, within the time of planning

the goods issue, by running the management program, run the management program Reservation management

program.

Either to purge or to automatically set movement allowed indicators.

And then finally, we have seen what is a pick list.

A pick list.

Is a transaction.

That when you give a date to it on the plant, it tells you all the materials that are required to be

picked up off of reservations.

And the warehouse manager can just go pick them and keep the goods ready so that the person needing

those goods can come in and pick the goods.

That is reservations.


