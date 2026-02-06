=XLOOKUP(B1, Sheet1!B:B, Sheet1!E:E, "") 


=IF(ISNUMBER(MATCH(B1, Sheet1!B:B, 0)), "YES - SPOC Bank", "NO")


=XLOOKUP(B1, Sheet1!B:B, Sheet1!C:C, "Not a SPOC Bank")

=XLOOKUP(B1, Sheet1!B:B, Sheet1!D:D, "")