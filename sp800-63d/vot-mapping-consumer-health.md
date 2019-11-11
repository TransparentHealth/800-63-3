### VoT Components for Consumer Health

This document uses the four components defined in VoT: Identity Proofing (P), 
Primary Credential Usage (C), 
and Assertion Presentation (A). This document does not define any additional component categories.

The VoT [component P](https://tools.ietf.org/html/draft-richer-vectors-of-trust-07#section-2.1) corresponds to identity proofing requirements and recommendations found in [SP 800-63A](sp800-63a.html). As such, the document maps SP 800-63's Identity Assurance Level (IAL) and identity proofing characteristics into VoT's P.

The VoT [component C](https://tools.ietf.org/html/draft-richer-vectors-of-trust-07#section-2.2) corresponds to authentication requirements and recommendations found in [SP 800-63B](sp800-63b.html). As such, this document maps SP 800-63's Authenticator Assurance Level (AAL), authenticator types, and authentication characteristics into VoT's C.

The VoT [component M](https://tools.ietf.org/html/draft-richer-vectors-of-trust-07#section-2.3) corresponds to authenticator lifecycle management requirements and recommendations found in [SP 800-63B Section 6](sp800-63b.html#sec6). As such, this document maps SP 800-63's authenticator lifecycle management characteristics into VoT's M.

The VoT [component A](https://tools.ietf.org/html/draft-richer-vectors-of-trust-07#section-2.4) corresponds to federation requirements and recommendations found in [SP 800-63C](sp800-63c.html). As such, this document maps SP 800-63's Federation Assurance Level (FAL) and assertion presentation into VoT's A.

**Table: 800-63 General Mapping to VoT Components**

|VoT Component|SP 800-63 xAL|SP 800-63 Requirements and Recommendations|
|:----:|:--:|:--:|
|P|IAL|identity proofing characteristics|
|C|AAL|authenticator types and authentication characteristics|
|A|FAL|assertion presentation|


### Identity Proofing

This section defines a series of `P` component values dervied from [SP 800-63A](sp800-63a.html).

#### IAL Values

|IAL|Component Value|
|:----:|:--:|
|IAL1 (with no attributes)|P0|
|IAL1|P1|
|IAL2|P2|
|IAL3|P3|


### Authentication Events

This section defines a series of `C` component values dervied from [SP 800-63B](sp800-63b.html).

#### AAL Values

|AAL|Component Value|
|:----:|:--:|
|AAL1|C1|
|AAL2|C2|
|AAL3|C3|




### Federation and Assertions

This section defines a series of `A` component values dervied from [SP 800-63C](sp800-63c.html).

#### FAL Values

|FAL|Component Value|
|:----:|:--:|
|FAL1|A1|
|FAL2|A2|
|FAL3|A3|


### Summary

The table below describes the values the values to be" sections to conform to this publication.

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

## References

[VoT] Vectors of Trust, December 8, 2018, available at: [https://tools.ietf.org/html/draft-richer-vectors-of-trust-07](https://tools.ietf.org/html/draft-richer-vectors-of-trust-07)
