# :airplane: Credit Rewards Converter :airplane:
This is the project repo for the JPMC Software Engineering Lite Program, consult the program instructions for more information.
create_with_cash_value Test:

Purpose: Verify that the RewardValue class correctly creates an instance with a specified cash value.
Steps:
Set a cash value of $100.
Create a RewardValue instance with the given cash value.
Use assertEquals to ensure that the retrieved cash value matches the expected value.
create_with_miles_value Test:

Purpose: Confirm that the RewardValue class successfully creates an instance with a specified miles value.
Steps:
Set a miles value of 10,000.
Create a RewardValue instance with the provided miles value.
Utilize assertEquals to verify that the retrieved miles value corresponds to the expected value.
convert_from_cash_to_miles Test:

Purpose: Validate the RewardValue class's ability to convert from cash to miles.
Steps:
Set a cash value of $100.
Create a RewardValue instance with the specified cash value.
Calculate the expected miles value based on the conversion rate (0.0035).
Use assertEquals with a delta of 0.0001 to ensure the calculated miles value matches the one returned by getMilesValue().
convert_from_miles_to_cash Test:

Purpose: Ensure the RewardValue class can accurately convert from miles to cash.
Steps:
Set a miles value of 10,000.
Create a RewardValue instance with the given miles value.
Calculate the expected cash value based on the inverse of the conversion rate (1/0.0035).
Use assertEquals with a delta of 0.0001 to confirm the calculated cash value matches the value returned by getCashValue().
