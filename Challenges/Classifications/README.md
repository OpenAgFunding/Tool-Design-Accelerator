![logo](http://i.imgur.com/TAfhGeGm.png)

## Classifications

Different users of data need different levels of detail. For some, seeing that a project relates to "Food Crop Production" (DAC Code: 31161) is sufficient, but others need to know exactly what crop the project relates to and this is where **sector specific classifications** can help.

IATI allows publishers to use non-embedded vocabularies to classify their activities, by using either code 98 or 99 in the sector vocabulary element of IATI. The Initiative for Open Ag Funding aims to utilise this by encouraging donors to start using the agriculturally specific vocabularies of either AGROVOC or GACS. AGROVOC, for example, consists of 32,000 concepts which define agriculturally relevant activities in both a hierarchical manner and to a high extent of granularity, for example:

`
Products (c_6211) > Plant Products (c_14477) > Vegetables (c_8174) > Soy beans (c_14477)
`

**However, **despite a strong user need, data publishers are concerned that manually tagging activities to such a detailed code list would require an unacceptable amount of time and resource. As our consultations with donors uncovered, the OECD DAC Purpose Codes are often preferred precisely because they are uncontroversial and lower effort. With this, if publishers are to use a more granular vocabulary to classify activities, we must resolve a number of challenges:

* Identify relevant and usable source material to classify the activities to a high level of detail. A [pilot study](https://docs.google.com/document/d/1fK7z_iqQvRrckftUx5NO36BwMAGSp6qxt0NZU_mGmAc/edit#) found that descriptions contained with the Raw IATI XML are rarely detailed enough but accompanying documents often are.

* Create a relevant subset of the vocabulary which is limited to the crops / livestock.

* Link the agricultural specific vocabulary with the OECD-DAC 5 Digit Purpose Codes.

* Automate the classification process but allow the publisher to check and confirm the recommended code.

<table>
  <tr>
    <td>Publication challenge</td>
    <td>User challenge</td>
  </tr>
  <tr>
    <td>Automate the classification process using a subset of relevant ontologies.</td>
    <td>Readily see where relevant activities are taking place to better leverage pre-existing projects or build partnerships.  </td>
  </tr>
</table>


*"If we knew that all the other organizations are working in maize, then we might work in soy or another crop to boost nutrition. We'll look to see if we can create a complementary program to what others are doing."* - Spring Consultation, 2016.
