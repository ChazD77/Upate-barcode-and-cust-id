UPDATE customers

SET BarCode = CustomerID

WHERE CustomerID = CustomerID

AND BarCode <> CustomerID


--this is how to set one column = another column

--this is setting the barcodes to be the same as the customerid's (the customer ids are unique. some of the barcodes have duplicates, but setting the barcode to = customer id makes the barcodes unique)
