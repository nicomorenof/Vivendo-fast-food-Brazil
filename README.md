# Vivendo-fast-food-Brazil


Vivendo is a fast food chain in Brazil with over 200 outlets.
Customers often claim compensation from the company for food poisoning.
The legal team processes these claims. The legal team has offices in four locations.
The legal team wants to improve how long it takes to reply to customers and close claims.
The head of the legal department wants a report on how each location differs in the time it
takes to close claims.

The dataset contains 8 different variables described here:
<table>
  <tr>
    <th>Column name</th>
    <th>Criteria</th>
  </tr>
  <tr>
    <td>claim_id</td>
    <td>Nominal. The unique identifier of the claim.
Missing values are not possible due to the database structure.</td>
  </tr>
    <tr>
    <td>time_to_close</td>
    <td>Discrete. The number of days to close the claim. Any positive
value.
Replace missing values with the overall median time to close.</td>
  </tr>
  <tr>
    <td>claim_amount</td>
    <td>Continuous. The initial claim requested in the currency of Brazil,
rounded to 2 decimal places.
Replace missing values with the overall median claim amount.</td>
  </tr>
    <tr>
    <td>amount_paid</td>
    <td>Continuous. Final amount paid. In the currency of Brazil. Rounded
to 2 decimal places.
Replace missing values with the overall median amount paid.</td>
  </tr>
    <tr>
    <td>location</td>
    <td>Nominal. Location of the claim, one of “RECIFE”, “SAO LUIS”,
“FORTALEZA”, or “NATAL”.
Remove missing values.</td>
  </tr>
    <tr>
    <td>individuals_on_claim</td>
    <td>Discrete. Number of individuals on this claim. Minimum 1 person.
Replace missing value with 0.</td>
  </tr>
    <tr>
    <td>linked_cases</td>
    <td>Nominal. Whether this claim is linked to other cases. Either TRUE or
FALSE.
Replace missing values with FALSE.</td>
  </tr>
    <tr>
    <td>cause</td>
    <td>Nominal. Cause of the food poisoning. One of “vegetable”, “meat”
or “unknown”.
Replace missing values with ‘unknown’.</td>
  </tr>
</table>
