# Checkout Groups - Fieldset

In [exercise 21](/week-3/21-dietary), you used `<fieldset>` and `<legend>` to group checkboxes together. In this exercise, you will use these tags to describe a group of fields that are related to each other.

To send the t-shirt to your customer you need to know where they want it to be delivered. This may be different from the address on the card they use to make payment. In this exercise, you will create two groups of fields: one for the billing address and one for the delivery address.

1. Find the line in the `index.html` page where it says `<!-- Add the form fields here -->`.
2. Below this line, add a `<fieldset>` with a `<legend>` that says "Billing Address".
3. Add text input fields nested inside of the `<fieldset>`. Add fields for the following: Address Line 1, Address Line 2, Postcode and City.
4. Repeat steps 2 and 3 for a set of fields named "Delivery Address".

_Hint: Every field needs a unique `name` attribute. You can't have two fields named `postcode`, so you will need to name each set differently._

When you are done, it should look like this.

![Screenshot of the billing and delivery address fieldsets](/images/26/solution.png)

<fieldset>
    <legend>billing address</legend>
    <label for="address1">address line 1</label>
    <input type="text" id="adress1" name="address1"><br><br>
    <label for="address2">address line 2</label>
    <input type="text" id="adress2" name="address2"><br><br>
    <label for="address3">postcode</label>
    <input type="text" id="adress3" name="address3"><br><br>
    <label for="address4">city</label>
    <input type="text" id="adress4" name="address4"><br><br>
  </fieldset>
