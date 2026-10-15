# odoo Whatsapp AI integration

When the user will send msg in odoo whatsapp which is integrated. By default the message's data is stored in odoo.

When the message will come in odoo whatsapp ai will check automatically that what is contact no and user's name.
Then it will check in res.partner that wather is partner is already created in odoo or this is new one.

If not craeted will craete a new one in partner.
If craeted then it will check wather any lead is connected with user. and what is it's status.

Then based on user's new message it will answer the user and change in crm.lead's stage or fiels of user.

For example if a user type that: i want to schedule a meeting on monday.
in follow-up field of crm.lead it will update that user want to join a meeting.

Same will happend for a stange changes and all.
while odoo has whatsapp's chat stored. so that AI will use that database everytime the user messages to maintain the context of old chat.

For update in CRM and for lead creation and user creation different tools are used, which are odoo's methods.

Also AI will make sure that it will not merge the chat or context of two different user. and one user may have multiple lead so that it do not 
conflicts with each other.

If any ambiguty happend then during this case it will tell user to contect their support manager.

If user will tell something like this then it will
