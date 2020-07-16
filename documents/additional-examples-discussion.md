Output of conversations arising from review last week triggered a need for additional scenarios to explain how the new ecosystem works outside of the basic 'Leermiddelenlijst - all pre-paid' flow.

The following are intended to articulate the types of flows that could be possible, and while not exhaustive should help visualise what is possible.

## Vocational - Individual Purchase - Marketplace integrated in ecosystem

1. A Learner in a vocational school is sent a list of material that they should purchase for the subjects they are studying (this could be via a system or just a document).
2. The school has relationships with two Marketplaces, one of which is integrated into the ecosystem and configured with the schools systems.
3. The learner clicks a link in the list for the Marketplace they want to use, and we assume that the Marketplace they click is integrated into the ecosystem for the school.
4. The learner logs in to the Marketplace with their School Identity, so that the Marketplace understands which school they are attending.
5. The learner purchases product A directly via ideal.
6. The Marketplace sends the information about the purchase to the Learning Application Provider who sells product A [standard step OA.3.4]
7. The Marketplace sends the information about the purchase to the LMS so the student can now see the product [standard step OA.3.2]
8. It is likely the Marketplace also informs the learner of the purchase etc. via email.
9. The learner can now access the product via the schools LMS.

## Vocational - Individual Purchase - Marketplace not integrated in ecosystem

1. A Learner in a vocational school is sent a list of material that they should purchase for the subjects they are studying.
2. The school has relationships with two Marketplaces, one of which is integrated into the ecosystem and configured with the schools systems.
3. The learner clicks a link in the list for the Marketplace they want to use, and we assume that the Marketplace they click is not integrated.
4. The learner creates an account in the Marketplace with their email address, and as a result the Marketplace does not know which school they are attending.
5. The learner purchases product A directly.
6. The Marketplace sends the information about the purchase to the Learning Application Provider who sells product A [standard step OA.3.4]
    - Note: If the marketplace is a large scale consumer service such as bol.com, it is envisaged that the LA uses the standard bol.com retailer API to replicate the data flow in OA.3.4.
8. It is likely the Marketplace also informs the learner of the purchase etc. via email.
9. The LA sends an email to the user instructing them how to access the product they have just purchased.
10. The LA cannot update the schools LMS as it does not have this information for this transaction.
11. The learner can now access the product. 

## Secondary - Material available and selected as Post Pay - based on first usage

1. LAP has made Product A available in a Marketplace under two commercial models - Pre-Pay and Post-Pay.  These have different pricing structures.  This information is exchanged in the catalogue.
2. LMC selects Product A under Post-Pay for their school when creating their LML.
3. Marketplace shares this information with the LA provider for Product A.  [standard step OA.3.4]
4. Marketplace shares this information with the schools LMS. [standard step OA.3.2]
5. A learner later accesses (and so automatically activates) Product A via a link in the LMS.  The LMS can choose to display (or not) that the product is charged based on usage.
6. On this first access the LA makes the data available to the Marketplace. [standard step OA.4.4]
7. The Marketplace invoices the school as per agreed terms (e.g. monthly based on new activations).

## Primary / Secondary - Material available as Freemium > Subscription after 30 days

1. LAP has made additional practicing material available in a Marketplace under a freemium model.  This product is expected to be paid for by parents under this model.
2. The LMC has selected this product as optional material in the LML, and so the selection is passed on to the LMS and LA by the standard exchanges.  This allows the LMS to make it visible to a teacher (in some way).
3. During the course of the year a Teacher selects this product to be used by a specific learner in the LMS, and the learner begins using it.
4. On first usage the LA exchanges this data with the Marketplace.  [standard step OA.4.4]
5. The Marketplace records the start of the free trial period of 30 days, and sends an email to the parent of the learner to notify them of this. The Marketplace has this information from the SIS of the school.
6. As the trial period nears its completion, the parent is emailed again to provide payment information and directly pay via the Marketplace.
7. If they pay, the learner can continue accessing the product.
8. If they do not pay, the access is blocked by the LAP.

## Primary / Secondary - Material available as one off purchase

1. LAP is advertising their product directly to parents.
2. When a parent clicks on a link in an advertisement, they are taken to the Marketplace provided by the LAP.  
3. The parent directly pays for the product.
4. The parent is emailed with information (or it is displayed in their account page) as to how their child can access the product.
