# bigtree-one-to-many-advanced-field-type
An advanced one-to-many field for BigTree CMS.

This field has two additional features at present.

The first is a field option which allows the user to select a second title field from the table that will be used in the rendered dropdown. For example, a common use is to select a One-to-Many field to show a list of custom users whose names are split into first name and last name in the database table. By selecting last name for the first title field and first name for the second title field the dropdown will display "Doe, John" instead of just "Doe".

The second is an Add Item button label override. For example, in the above scenario, when the one-to-many control is rendered, you could set the label to say, Add User, instead of Add Item.
