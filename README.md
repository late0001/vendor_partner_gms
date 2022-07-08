# vendor_gapps
Android 11 ARM64 GAPPS

To build your GAPPS in your rom simply include:

vendor/partner_gms/sagit/sagit-vendor.mk

into your device makefile.

e.g:

$(call inherit-product-if-exists, vendor/partner_gms/sagit/sagit-vendor.mk)

or

-include vendor/partner_gms/products/sagit-vendor.mk
