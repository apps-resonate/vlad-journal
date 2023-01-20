## Fields descriptions

*Descriptions acquired from Monday.com issue*
-   Lease Period (Date) MM/DD/YY format:
    -   From
    -   To
-   Monthly Rent (numeric in peso):
-   Number of Occupant (numeric)
-   Number of Parking Slot (numeric)
-   Pets (Dropdown)
    -   Option 1: Yes - If Yes, add an input field:
        -   Specify Pet if dog, cat, etc (freetext)
    -   Option 2: No
-   Security Deposit (Dropdown)
    -   Option 1: Two (2) Months
    -   Option 2: Others - If Others is selected, add an input field
        -   inputfield - freetext
-   Payment Terms (Dropdown)
    -   Option 1: One (1) Year Advanced Rent Payment
    -   Option 2: Others - If Others is selected, add an input field
        -   inputfield - freetext
-   Pre-Termination (Dropdown)
    -   Option 1: This lease is guaranteed for the entire duration of this Contract of Lease
    -   Option 2: Others - If Others is selected, add an input field
        -   inputfield - freetext
-   Special Requests (freetext)

## Fields datatypes

-   User: `user: references` → `user_id`
-   Lease Period From: `lease_period_from: date`
-   Lease Period To: `lease_period_to: date`
-   Monthly Rent (numeric in peso): `monthly_rent:  money` → `monthly_rent_cents`
-   Number of Occupant\*s (numeric): `number_of_occupants: integer`
-   Number of Parking Slot (numeric)): `number_of_parking_slots: integer`
-   Pets
	-   `has_pets: text, default:null`
	-   If yes, require text input. Else, null.
-   Security Deposit
	-   `security_deposit: text`
	-   default option: “Two (2) Months”
	-   others: input custom text. require input
-   Payment Terms (Dropdown)
	-   `payment_terms: text`
	-   default option: “One (1) Year Advanced Rent Payment”
	-   others: input custom text. require input
-   Pre-Termination (Dropdown)
	-   `payment_terms: text`
	-   default option: “This lease is guaranteed for the entire duration of this Contract of Lease”
	-   others: input custom text. require input
-   Special Requests (freetext):  `special_requests: text`