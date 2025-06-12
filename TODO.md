# TODO

- The new step to add shipping information to an order should take this data from somewhere instead of hardcoding some values (see `src/OrderTaking/PlaceOrder.Implementation.fs#L398`)
- we still need to add the match when creating events at the end of the workflow
- remove the temporary choice type `OrderToAcknowledge` we introduced at the beginning
