This dataset covers the "Customer Support" domain.

It contains 27 intents (grouped in 11 categories). These intents have been selected from Bitext's collection of datasets for 20 domains (banking, retail, utilities...), keeping the intents that are common across domains.

The core dataset contains over 20,000 utterances, with a varying number of utterances depending on the intent (between 100 and 4000).

The utterances have been extracted from a larger dataset of 288,000 utterances (approx. 10,000 per intent), including language register variations such as politeness, colloquial, swearing, indirect style...

To select the utterances, we profiled the language register use in user queries from a wide range of customer support bots, and used stratified sampling to generate a dataset with a similar language register profile.

In this latest revision, we have also introduced noise into the utterances, including spelling mistakes, run-on words and missing punctuation, making the training data even more realistic, and making your bots more robust to the type of noise that is common in production.

The dataset is delivered in a comma-separated UTF-8 text file. It contains three fields: the utterance, its category and its intent.

Intents:
	cancel_order
	complaint
	contact_customer_service
	contact_human_agent
	create_account
	change_order
	change_shipping_address
	check_cancellation_fee
	check_invoices
	check_payment_methods
	check_refund_policy
	delete_account
	delivery_options
	delivery_period
	edit_account
	get_invoice
	get_refund
	newsletter_subscription
	payment_issue
	place_order
	recover_password
	registration_problems
	review
	set_up_shipping_address
	switch_account
	track_order
	track_refund

Categories:
	ACCOUNT
	CANCELLATION_FEE
	CONTACT
	DELIVERY
	FEEDBACK
	INVOICES
	NEWSLETTER
	ORDER
	PAYMENT
	REFUNDS
	SHIPPING
