## Fixed the issue that WHMCS invoice PDF could not display Chinese characters

- Upload the three files in the droidsansfallback folder to /vendor/tecnickcom/tcpdf/fonts/
- Go to Configuration () > System Settings > General Settings or, prior to WHMCS 8.0, Setup > General Settings. Select the Invoices tab.
- Select Custom and enter **droidsansfallback** for PDF Font Family.
- Click Save Changes.
