<Can the same medication be dispensed to the same patient more than once per day?, Constraint> This will impose a 
limit on the patient for the number of times they can dispense the same medication

<Is there a maximum allowable dose for a medication?, Invariant> This is an invariant as the dosage must always
be lower than the maximum

<How does the system get the information about the dispensing event?, Functional> This is functional as it is about how
the system works (its functions)

<Is there an authorization/verification process for the system to verify that the prescription matches the dispensing 
events?, Invariant> The dispensed medication must always match a prescription.

<Does the system keep track of a medication's schedule in order to prevent misuse other than not dispensing twice in the
same day?, Constraint> This is a constraint as it would set more restrictions on how the patient can use the medication

<How does the system obtain the maximum dosage limits of the medications?, Functional> This is functional as it is not
about the enforcement of the dosage limit but how it is obtained

<Does the system only allow the patient to access medications at a certain time?, Constraint> This would prevent the
patient from accessing it at other times thus being a constraint

<Does the system keep track of refills?, Constraint> Another constraint as it prevents the patient from acessing the
prescription more than a certain number of times

<How does system verify that the correct patient has received the medication if there are multiple patients?,Functional>
Functional as it correlates more to the capabilities of the system as opposed to constraining it.

<Is the system made to be used by patients directly or by a health practitioner on their behalf?, Functional> This is
functional as it is moreso about the general usecase of the system itself not constraining people to it.