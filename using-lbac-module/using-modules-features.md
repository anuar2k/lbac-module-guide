# Using module's features

Although LBAC module infact modifies the behavior of some parts of the system rather than introducing new functionality, there's some new functions we've covered here:

### Change the location of already registered patient

If you want to move a patient to another location, please open the summary page of the patient you want to move and follow these steps:

![Enter Edit Patient Location](../.gitbook/assets/x.png)

![then select a new location, click &quot;Confirm&quot;](../.gitbook/assets/y.png)

![and hit &quot;Confirm&quot;](../.gitbook/assets/z.png)

{% hint style="success" %}
Congrats! You've changed the location assigned to a patient.
{% endhint %}

### Show/hide location selector on the login page \(optional functionality\)

You can **show/hide the location selector** **following these steps:**

![Go to the System Administration page](../.gitbook/assets/a.png)

![then select Manage Global Properties](../.gitbook/assets/h.png)

Now, you have to find `referenceapplication.locationUserPropertyName` property on the list. Now click "edit" button on the right of the property name, and to:

* enable the location selector, set the Value to `false`
* disable the location selector, set the Value to `locationUuid`

![](../.gitbook/assets/w.png)

{% hint style="success" %}
Click "Save" and that's everything!
{% endhint %}



