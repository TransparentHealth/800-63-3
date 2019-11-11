### OpenID Connect / Vectors of Trust Profile For Consumer Health

This document maps NIST SP 800-63-3 to Vectors of Trust. It defines a profile for Open ID Connect servers and relying parties wishing to communicate `IAL` and `AAL` in a simple and consistent way.

* For Open ID Connect Providers - The `id_token` SHALL contain the claim `vot`. that can be made up of one or more of the following values in the table to follow.  For example, `P2.C2` means `IAL2` and `AAL2`.
* For Relying Paties - The `id_token` should interpret the contents of the `vot` claim. The values may control access to  authorizations based on situatition specific business rules. 

The table below describes the valid values and to be contained

|Component Value| NIST SP 800-63-3|
|:----:|:--:|
|P0|IAL1|
|P1|IAL1|
|P2|IAL2|
|P3|IAL2|
|C1|AAL1|
|C2|AAL2|
|C3|AAL3|
|A1|FAL1|
|A2|FAL2|
|A3|FAL3|


**Table: 800-63 General Mapping to VoT Components**

|VoT Component|SP 800-63 xAL|SP 800-63 Requirements and Recommendations|
|:----:|:--:|:--:|
|P|IAL|identity proofing characteristics|
|C|AAL|authenticator types and authentication characteristics|
|A|FAL|assertion presentation|


####  IAL Values

|IAL|Component Value|
|:----:|:--:|
|IAL1 (with no attributes)|P0|
|IAL1|P1|
|IAL2|P2|
|IAL3|P3|


#### AAL Values

|AAL|Component Value|
|:----:|:--:|
|AAL1|C1|
|AAL2|C2|
|AAL3|C3|



#### FAL Values

|FAL|Component Value|
|:----:|:--:|
|FAL1|A1|
|FAL2|A2|
|FAL3|A3|


## References

[VoT] Vectors of Trust available at: [https://tools.ietf.org/html/rfc848](https://tools.ietf.org/html/rfc848)
