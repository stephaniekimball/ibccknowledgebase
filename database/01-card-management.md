# Card Management: Replacement, Activation and Freezing

## CARD ELIGIBILITY
- Account must be Active and not delinquent to receive any card
- Virtual card available immediately upon approval
- Physical card: up to 10 business days via USPS, no tracking, cannot ship to PO Box

## CARD TYPES
- Account Owner: METAL card
- Authorized Users: PLASTIC card

## FIRST PHYSICAL CARD
Must be self-serviced through mobile app. Agents CANNOT place first order in Admin Portal.

## ACCOUNT OWNER vs AUTHORIZED USER
- Account Owner: Can order/replace their own card and AU cards. To order/replace AU physical card = must call in.
- Authorized User: Can replace their own virtual or physical cards via mobile app or phone. Cannot order/replace cards for other users.

## CARD ACTIVATION IN ADMIN PORTAL
1. Pull up account
2. Validate caller
3. Locate card - confirm last 4 digits and cardholder name
4. Request customer verify card details (name, card type, last 4)
5. Click 'Activate Card'
6. Inform card is active; can add to mobile wallet
7. Brand call, disconnect
8. Update Salesforce, assign Tier-1 Closed, add Admin note

Note: Cannot activate on web dashboard

## REPLACEMENT RULES
- 15-Day Rule (Physical only): Must wait 15 calendar days if card not received
- Immediate reorder exceptions: Damaged, sent to wrong address, stolen after activation

## CARD REPLACEMENT IN ADMIN PORTAL
1. Pull up account
2. Validate caller
3. Confirm reason:
   - Lost/Stolen: Verify Active → step 4
   - Never Received <15 days: Ask caller to wait → step 11
   - Never Received >15 days: step 4
   - Damaged/Activation Issue: Verify Active → step 4
   - Found by 3rd Party: Do NOT disclose account info. Get printed name + last 4. Ask to destroy card. Assign to Tier-3.
   - Name Change: Assign to Tier-3
4. Locate card in Admin Portal → Profile tab → search name → verify last 4 + format
5. If physical card Pending: activate it first (step 6), then proceed
6. Activate card first if needed
7. Click 'Replace' (verify last 4, name, card type)
8. Select replacement reason
9. Inform: virtual = immediate; physical = 10 business days
10. If lost/stolen: check for unauthorized transactions. If found, initiate dispute.
11. Brand call, disconnect
12-14. Update Salesforce, assign Tier-1 Closed, add Admin note

## FREEZE/UNFREEZE IN ADMIN PORTAL
1. Pull up account
2. Validate
3. Confirm cardholder name + card type → navigate to Freeze/Unfreeze sub-tab → click button
4. Refresh to verify status updated
5-8. Brand/disconnect, update Salesforce, assign Tier-1 Closed, add Admin note

## INTERNATIONAL TRANSACTIONS
- Must be manually enabled; Account Owner only (AUs cannot modify)
- Mobile: Login → Profile → Your Card → International Usage toggle
- Online: Login → Profile → Your Card → International Usage

## ADDING AU (Mobile App only)
1. Login → Your cards → '+' icon
2. Enter: First Name, Last Name, Phone, DOB, Credit Limit
3. Check permission box → Submit → Send invite → manually tap Send

## REMOVING AU (Mobile App only)
1. Login → Your cards → select AU image → AU profile
2. Scroll to bottom → 'Remove User' → Yes to confirm

**Keywords:** card, replace, activate, freeze, lost, stolen, physical, virtual, AU card, international