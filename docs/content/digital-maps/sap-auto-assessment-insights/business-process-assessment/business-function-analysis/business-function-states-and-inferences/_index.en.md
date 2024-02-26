---
title: "S/4HANA Business Function States"
date: 2024-01-28T11:02:05+06:00
lastmod: 2024-02-25T11:02:05+06:00
weight: 27
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

</br>1. A business function in SAP ECC can have only two states, Active (ON) and Inactive (OFF). However, a business function usually has one of the following three states in S/4HANA:

<ul>
i. Always ON 
</br>ii. Always OFF
</br>iii. Customer Switchable
</ul>

![](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Maps/37_business_function_state_process_assessment_digital_maps.png)

</br>2. The above table indicates the various permutations and combinations with respect to the status of each business function. 

### Inferences for each of the Business Function States

</br>1. The following inferences can be made from the above table:

<ul>
i. If a business function is switched on in your SAP ECC landscape, but the corresponding S/4HANA state is always OFF, then you cannot go for conversion. You will have to wait until SAP makes the business function compatible with S/4HANA or release a patch or have a look at the roadmap and then plan the transition.

</br>ii. If a business function is switched off in the ECC system, but the corresponding S/4HANA is always ON, then the conversion is possible and the business function will be switched on after the transition. You will have to assess the implications of such a business function being switched on in S/4HANA.

</br>iii. If the business function state in S/4HANA is customer switchable, then the conversion is possible and the state of the business function remains the same as before the transition, i.e these business functions keep their state after the conversion.
</ul>

</br>2. KTern simplifies this process by identifying the state of the business functions in SAP ECC and analyzing whether the functions are compatible with S/4HANA or not. 

</br>3. With this information, the solution architects and the respective functional consultants can make the above inferences with ease.

</div>