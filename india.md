# India

[IndiaStack](http://indiastack.org) is the name of the programme to develop a set of national-wide platforms for identity and finance.

## Platforms

### Aadhaar

12 digit number. Inputs can be checked for validity (of the number) using  [Verhoeff checksum](http://apps.nic.in/apps/government/aadhaar-number-validation-verhoeff-algorithm).

The Indian government [maintains a list of supported biometric sensors](http://www.stqc.gov.in/sites/upload_files/stqc/files/List%20of%20BiometricDevices_readywith%20RD%20service_14-08-2017.pdf).

### eKYC

Proof of identity and address using Aadhaar. If authentication is sucessful, the follow data gets returned:

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

### UPI

### Digilocker

### eSign