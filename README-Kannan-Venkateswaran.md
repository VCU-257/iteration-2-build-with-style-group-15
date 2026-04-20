# Student Name: Kannan Venkateswaran

## 1. My Assigned Work
For Part 3 (Adding Interaction), I implemented the Payment + Validation interaction stream.

- Updated page: payment.html
- Added client-side validation with custom rules for:
	- Name on card (required, minimum length)
	- Card number (16 digits, auto-formatted while typing)
	- Expiration date (must not be in the past)
	- CVV (3 to 4 digits)
	- Billing address, city, state (2-letter code), and ZIP (5 digits)
- Added dynamic UI behaviors:
	- Dismissible alert box that shows error/success states
	- Real-time input formatting and immediate feedback with valid/invalid styles
	- Submit button processing state with spinner
	- Redirect to payment-validation.html after successful client-side validation


## 2. AI / LLM Usage
*Did you use an AI tool to help write or debug your code?*
* **What I asked the AI:** "How should I best design the code to ensure that there are no debugging errors without you doing the assignment yourself."
* **How it helped & What I learned:** The AI helped me design and implement structured client-side validation and dynamic feedback behavior in vanilla JavaScript with Bootstrap classes. I learned how to combine custom validation logic, real-time input sanitization/formatting, dismissible alerts, and submit-state UX (spinner + redirect) into a complete interaction flow. I verified understanding by reviewing each validation function, testing valid/invalid cases in the form, and confirming that successful submission redirects correctly.

## 3. Live Site Link
*Provide the GitHub Pages link to the specific page(s) you built.*
* **Live URL:** https://vcu-257.github.io/iteration-2-build-with-style-group-15/payment.html