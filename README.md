![Logo](https://repository-images.githubusercontent.com/314212293/56574f00-2f00-11eb-81c6-7f2def9c2bcc)
## PSGC (Philippine Standard Geographic Code) [![Made by](https://img.shields.io/badge/Made%20with%20%F0%9F%92%9C%20by-Justin%20Balaguer-15202B.svg?longCache=true&style=for-the-badge)](https://justinbalaguer.github.io/)

API used for listing all the region, province, city, municipality, and barangay. All data came from
[Philippine Statistics Authority](https://psa.gov.ph)
This API includes the total population for each regions etc. and other information.\
![Updated Data](https://img.shields.io/badge/Data-as%20of%20June%202020-green.svg)\
![Github Stars](https://img.shields.io/github/stars/justinbalaguer/PSGC-API.svg?style=for-the-badge)
![Github Forks](https://img.shields.io/github/forks/justinbalaguer/PSGC-API.svg?style=for-the-badge)
![Github License](https://img.shields.io/github/license/justinbalaguer/PSGC-API.svg?style=for-the-badge)
![Made With](https://img.shields.io/badge/Made%20with-Node.JS-68A063?style=for-the-badge&logo=Node.JS)

## DOCS
[Postman](https://documenter.getpostman.com/view/12270232/TVmFmLrt)

## ENDPOINTS (v1.2)

METHOD | Base URL
------------ | -------------
GET | [`https://psgc.vercel.app/`](https://psgc.vercel.app/)

### REGION
Data | Endpoint
------------ | -------------
All Region | ```api/region```
Specific Region | ```api/region/{{code}}```
List of Province in specific Region | ```api/region/{{code}}/province```

### PROVINCE
Data | Endpoint
------------ | -------------
All Province | ```api/province```
Specific Province | ```api/province/{{code}}```
List of City in specific Province | ```api/province/{{code}}/city```
List of Municipality in specific Region | ```api/province/{{code}}/municipality```

### CITY
Data | Endpoint
------------ | -------------
All City | ```api/city```
Specific City | ```api/city/{{code}}```
List of Barangay in specific City | ```api/city/{{code}}/barangay```

### MUNICIPALITY
Data | Endpoint
------------ | -------------
All Municipality | ```api/municipality```
Specific Municipality | ```api/municipality/{{code}}```
List of Barangay in specific Municipality | ```api/municipality/{{code}}/barangay```

### BARANGAY
Data | Endpoint
------------ | -------------
All Barangay | ```api/barangay```
Specific Barangay | ```api/barangay/{{code}}```

## SOCIALS
[![Twitter](https://img.shields.io/badge/@ojintoji-Twitter-00acee.svg)](https://twitter.com/ojintoji/)\
[![Twitter](https://img.shields.io/badge/@ojintojix-Facebook-3b5998.svg)](https://facebook.com/ojintojix/)
