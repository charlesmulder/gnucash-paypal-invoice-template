# PayPal invoice template for GnuCash

Original invoice templates available at ```/usr/share/gnucash/scm/gnucash/report/```

Create the below symlinks

```
ln -s $(pwd)/config.user ~/.gnucash/config.user
ln -s $(pwd)/saved-reports-2.4 ~/.gnucash/saved-reports-2.4
ln -s $(pwd)/paypal_taxinvoice.css ~/.gnucash/paypal_taxinvoice.css
ln -s $(pwd)/paypal_taxinvoice.eguile.scm ~/.gnucash/paypal_taxinvoice.eguile.scm
ln -s $(pwd)/paypal_taxinvoice.scm ~/.gnucash/paypal_taxinvoice.scm
```

Start GnuCash and navigate to ```Reports > Saved Report Configurations > PayPal Tax Invoice``` in the top menu

## Resources

* [Custom Reports Using Eguile](https://wiki.gnucash.org/wiki/Custom_Reports_Using_Eguile)
* [Custom Reports](https://wiki.gnucash.org/wiki/Custom_Reports)

