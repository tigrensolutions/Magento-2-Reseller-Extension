# Magento 2 Reseller Extension

<div class="list-features" style="text-align: justify;">Owing to the <em>Magento 2 Reseller Extension</em>, the Magento store owners can easily create a special program for their resellers - "big customers" at the store. In this program, the admin is able to create and assign the resellers to multiple groups and grant different rewards (discounts) for each group. 80% of the process is automatic, the admin just needs to make some initial configuration and make approval/ disapproval when there is a reseller registration request.</div>
<div class="list-features" style="text-align: justify;"></div>
<div class="list-features" style="text-align: justify;">
<div class="list-features" style="text-align: justify;">

Any general customer wholesaler or retailer (based on the admin configuration) can become a reseller as long as their total spending in a month satisfies the “entry-level” of any reseller group.

To understand how the <em>Magento 2 Reseller Extension</em> works, let's take a look at its flow:

</div>
<p style="text-align: center;"><span style="font-size: 25px; font-style: italic; color: #ff0000;"><strong>
HOW IT WORKS</strong></span></p>

![magento-reseller-extension-1-1024x236](https://user-images.githubusercontent.com/26241389/162147867-c364e764-496b-4cd5-a5db-1e93f04d8ad3.png)

<strong>Step 1: Reseller registration</strong>

In order to become resellers in the store, the customers must submit a Reseller Application Form. Then, they will receive an email notifying them that their request is under review.

<strong>Step 2: Admin approval </strong>

The admin will receive a notification email of new reseller registration once the request is submitted. Then, the admin will examine the provided information of the register before making an approval or disapproval.

<strong>Step 3: Reseller group assignment </strong>

After accepting the customer request, the admin is able to assign that customer to a certain group (for example: Silver, Gold, or Platinum).

<strong>Step 4: Discount acquirement for reseller</strong>

The resellers now will get a specific amount of discount (%) for all purchases depending on the groups they belong to.

<strong>Step 5: Rank promotion or demotion</strong>

The initial rank of the resellers won’t last permanently but change over time. Based on the money they spend on the store in a month, if that amount reaches the target of the higher reseller group, they will be promoted automatically.

By contrast, after a certain period of time, if their total spending is lower than the required minimum amount, they will be demoted or even are no longer a reseller.

It’s worth noting that all rank adjustments are based on the Calendar month, which means that the tier pricing is established from the 1<sup>st</sup> day of a month to the last day of that month.

![magento-reseller-extension-example-1024x282](https://user-images.githubusercontent.com/26241389/162148145-f08dd2d5-56ed-4db3-9ef9-326d6275e4ff.png)

In most cases, the customers must go through a <em>"<b>challenge month</b>" </em>before being assigned to a certain reseller group. For example, if a buyer is approved to be the reseller on the 15<sup>th</sup> of January, we will ignore the period from 15<sup>th</sup> January to 31<sup>st</sup> January. Then, the challenge time will start from the 1<sup>st</sup> of February to the last day of February. The total amount of customer expenditure in February will be the condition to assign him/ her to a group.

Assumed that there are 3 reseller groups as the following:
<table>
<tbody>
<tr>
<td width="240">
<p style="text-align: center;"><strong>Group</strong></p>
</td>
<td width="240">
<p style="text-align: center;"><strong>Entry Level</strong></p>
</td>
<td width="240">
<p style="text-align: center;"><strong>Discount</strong></p>
</td>
</tr>
<tr>
<td width="240">
<p style="text-align: center;">Silver</p>
</td>
<td width="240">
<p style="text-align: center;">$500/month</p>
</td>
<td width="240">
<p style="text-align: center;">10%</p>
</td>
</tr>
<tr>
<td width="240">
<p style="text-align: center;">Gold</p>
</td>
<td width="240">
<p style="text-align: center;">$1,000/month</p>
</td>
<td width="240">
<p style="text-align: center;">20%</p>
</td>
</tr>
<tr>
<td width="240">
<p style="text-align: center;">Platinum</p>
</td>
<td width="240">
<p style="text-align: center;">$1,500/month</p>
</td>
<td width="240">
<p style="text-align: center;">30%</p>
</td>
</tr>
</tbody>
</table>
&nbsp;

If the customers spend in the range of <b>$500 ≤ … &lt; $1,000</b> in February, they will be qualified in the <em>Silver </em>group and get 10% off for all orders from March. Next, in March if the customers consume equal to or more than $1,000 but lower than $1,500, they will be moved to the <em>Gold</em> group and get a 20% discount from April. On the other hand, if their total spending in March is just $400 for instance, they will remain in the <em>Silver </em>group.

If the customer spends <b>less than $500</b>, which is lower than the entry-level of all groups, he/ she will have another “challenge month” – March.
<h2 style="text-align: center;"><span style="font-size: 25px; font-style: italic; color: #ff0000;"><strong>
OUTSTANDING FEATURES OF MAGENTO 2 RESELLER EXTENSION
</strong></span></h2>
<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Create the custom reseller registration form</strong></span>

<span style="font-weight: normal;">Besides requiring basic information like any other forms (phone number, address, zip code,…), The <em>Magento 2 Reseller Extension</em> gives the admin the ability to add more custom questions for the registers. </span>

For example, asking about the motivation of the customers to become resellers, the main focus of their businesses, their plan of selling products after buying from the store, or their estimated spending per month would make the admin’s evaluation process become easier.

<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Create the reseller groups</strong></span>

<span style="font-weight: normal;">The admin can create multiple reseller groups from the back-end. </span>

The settings for each group will include:
+) Choosing qualified customer group (guest/ general/ wholesale/ retailer)
+) Defining the entry cost (in a month)
+) Determining specifically the discount amount for members of this group

</div>
<div class="col-md-6 col-2">
</div>
<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Set a target expenditure for each group</strong></span>

<span style="font-weight: normal;">For each group, the admin can set an entry-level, or in other words, minimum spending ($) in a month for a reseller to be qualified in that group. </span>

For example, the reseller must buy all orders with a total cost that is equal to or greater than <em>$500, $1,000,</em> or <em>$1,500 </em> to join the <em>Silver, Gold, </em>or <em>Platinum groups</em> respectively.

<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Set specific discount amounts for groups</strong></span>

<span style="font-weight: normal;">The reward for being a reseller is attractive discounts (%) for all purchases at the store. Depending on the group that the resellers belong to, they will receive a certain percentage of the discount.</span>

For example, a <em>Silver </em>group member just gets 10% off for his/ her orders while a <em>Gold </em>or <em>Platinum </em>one will get 20% or 30% off for any purchases.

<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Manually assign the reseller to a specific group</strong></span>

<span style="font-weight: normal;">Normally, the customer must go through 1 month after registering to become the reseller to see how much their spending would be before being assigned to a reseller group.</span>

However, in some special cases, the admin can immediately assign a customer to a group without the “challenge time”.

For instance, because of knowing that the register has been a loyal customer of the store for a long time with the high volume of monthly purchases (based on the order history), the admin can save that customer to the <em>Gold/ Platinum </em>reseller group right after approving his/ her request.

</div>

<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Set rules for reseller rank promotion or demotion</strong></span>

<span style="font-weight: normal;">For rank promotion, it’s simple. On the last day of each month, or called the <em>rank review day</em> the reseller’s total spending on that month will be reviewed and evaluated. If this amount is equal to or higher on the entry-level of the higher reseller rank, the reseller will be promoted automatically and get a higher discount percentage in the next month.</span>

For rank demotion, the admin can set the minimum amount of purchases over a certain period of time for the resellers to maintain their position in that group. If they cannot fulfill the requirement, they can be demoted to a lower rank or even be eliminated from all reseller groups.

For instance, if the resellers don’t make any orders/ spend $0.00 in 3 consecutive counted months, they will be terminated as the resellers and changed to regular customers.

</div>

<div class="row col2-set">
<div class="col-md-6 col-1">

<span style="font-size: medium; color: #000080;"><strong>Send notification emails to the resellers</strong></span>

<span style="font-weight: normal;">The customers will receive notification emails when submitting the reseller registration requests, getting results for approval/ disapproval from the admin, and being promoted or demoted. </span>

Especially, <em>Magento 2 Reseller Extension</em> allows the admin to send a special email to the resellers, showing the resellers' amount of purchases on that month and how much they should spend more to reach the higher rank or to maintain in the current group – X days prior to the end of the month.

For instance, there are only 5 days left before the rank review day. This month, the customer has spent $850 and now is in the <em>Silver </em>reseller group. The store can send an email encouraging customers to spend more than $150 to be promoted to the <em>Gold </em>group automatically.

In this way, the store can stimulate resellers’ spending wisely and effectively.

</div>

As you can see, the <strong><a href="https://www.tigren.com/magento-2-extensions" rel="nofollow">Magento 2 Reseller Extension</a></strong> is very useful but simple and easy to use. By using this plugin, you not only attract more people to become your resellers but also boost their purchases at your store.<strong>
</strong>

</div>
