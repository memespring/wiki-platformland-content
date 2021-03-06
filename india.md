# India
## National Cloud of NIC


[https://cloud.gov.in](cloud.gov.in) is run by the National Informatics Centre,  part of the Ministry of Electronics and Information Technology.

## IndiaStack

[IndiaStack](http://indiastack.org) is the name of the programme to develop a set of society-wide platforms for identity and finance. Although run/mandated by central government, the vision is for shared national infrastructure for use by government and beyond.

### Aadhaar

Aadhaar is a unique 12 digit number combined with demographic and biometric data. It is operated by the Unique Identification Authority of India (UIDAI), a statutory authority established in January 2009 by the government of India, under the jurisdiction of the Ministry of Electronics and Information Technology.

It gives [proof of residence, but not proof of citizenship](https://www.livelaw.in/aadhaar-card-not-proof-citizenship-calcutta-hc/).

Inputs can be checked for validity (of the number) using  [Verhoeff checksum](http://apps.nic.in/apps/government/aadhaar-number-validation-verhoeff-algorithm).

The Indian government [maintains a list of supported biometric sensors](http://www.stqc.gov.in/sites/upload_files/stqc/files/List%20of%20BiometricDevices_readywith%20RD%20service_14-08-2017.pdf).

### eKYC

Proof of identity and address using Aadhaar. If authentication is successful, the following data gets returned:

```
    User_Id: 'OUR SYSTEM USER ID',
    Aadhar_Id: '655XXXXXXXXX',
    e_Kyc: {
        status: 'y',
        Description: 'Authenticated Successfully',
        Code: '124be446983XXXXXXXXXXXXXXX',
        RRN: '6345XXXXXXXX',
        Poi: {
            Name: 'RESIDENT NAME HERE',
            Dob: 'DD-MM-YYYY',
            Gender: 'M'
        },
        Poa: {
            co: 'S/O: TEST NAME',
            house: 'ward no. 007',
            street: 'street name',
            landmark: 'landmark provided to Aadhaar',
            lc: 'locality',
            vtc: 'Panna',
            subdist: 'sub-district',
            dist: 'district',
            state: 'state name',
            pc: 'pin code',
            po: 'postal code',
            uidtag: 'AAPKA AADHAAR'
        },
        Photo: 'base-64-image-data-here'
    },
    payload: 'complete response in base64 encoded format',
    qTid: '',
    resident_authentication: '',
    transactionId: 'QT-6559XXXXXXX-OXXXXXXXX',
    time: 'DD/MM/YYYY, HH:MM:SS PM',
    ver: '2.1'
}
```

[source](https://aadhaarapi.com/aadhaar-response-format/)

### Unified Payment Interface (UPI)

A nationwide and economy-wide payments system. Users can send or request money using different identifiers (Aadhaaar number, phone number, bank account or 'virtual payment address')

### Digilocker

[DigiLocker](https://digilocker.gov.in) personal data store for signed documents / digital proofs. It is operated by the Ministry of Electronics & Information Technology. It uses Aadhaar for linking government documents (although it is possible to use DigiLocker without linking it to an Aadhaar account [citation needed].

[It is possible to add a digital driving licence to DigiLocker](https://indianexpress.com/article/what-is/digilocker-indian-railways-id-proof-aadhaar-card-driving-licence-upload-documents-5246808/). Driving licences and Aadhaar accounts in DigiLocker can be used as valid identity documents for travelling on India Railways.



### eSign

eSign is a service for signing documents using an Aadhaar identity.
