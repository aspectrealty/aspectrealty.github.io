# Aspect Realty

### Static Site Generator

## Updating Properties

Properties are generated using markdown files located in the [_properties](https://github.com/aspectrealty/aspectrealty.github.io/tree/master/_properties) folder.

To add a new property simply copy the contents of an existing property file and paste into a new file in this directory.  Fill out the fields and then click the 'Commit new file' button at the bottom of the page.  This will trigger the website to generate and the new property should show within 10 minutes.

ex. property.md file:

```
---
address1: 1115 Chambers Ave. Unit B101
address2: Eagle, CO 81657
sqft: 1000
term: 2-5 Years
camretax: Included in Rent
shortdesc: Office Retail, Light Industrial
agent: Jason Fish
phone: 970-300-1415
email: jfish@aspectrealtyco.com
price: $17.00-$20.00 SF Annual
desc: B101 is a new commercial space in the Chambers Lofts mixed use complex in Eagle directly facing Chambers Avenue. This unit is ready for any office, retail, or warehousing tenant needs. This space gets ample natural sunlight as it is equipped with two 10 foot glass overhead doors along with a south facing orientation. The unit was configured to maximize functional use without compromising an aesthetically pleasing storefront, which directly addresses Chambers Avenue. This particular has access to a private patio for outside seating or additional displays and is fully stubbed for water, gas and electric. Call for more details regarding landlord fit out incentives to make this space fit any of your operational needs.
mapurl: https://www.google.com/maps/embed/v1/place?key=AIzaSyBxhIcjBcpDa3pzvGqgMLnSgZDusFYQci4&q=1115+Chambers+Ave,+Eagle,+CO+81631
gallery: property1
---
```

## Property Images

Each property's gallery is mapped to a directory named in the markdown file.  The property page will look for a folder with the name used in the 'gallery' field in the [assets/images](https://github.com/aspectrealty/aspectrealty.github.io/tree/master/assets/images) directory.

## Other Images

The only other important file location is the [img](https://github.com/aspectrealty/aspectrealty.github.io/tree/master/img) folder.  This folder holds the images for the header background, logo, headshot, and about section.  If needed, just replace these images and commit to regenerate the website.