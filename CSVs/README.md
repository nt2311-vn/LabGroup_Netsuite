## CSV Import Guidance

### Preparing Your CSV File

1. Ensure your CSV file has the correct headers as per the NetSuite template.
2. Each column should represent a field in NetSuite.
3. Save your CSV file in `.csv` **UTF-8** format.

### Importing CSV Files

1. Go to **Setup** > **Import/Export** > **Import CSV Records**.
2. Choose the type of record you are importing.
3. Upload your CSV file.
4. Map the CSV columns to the corresponding NetSuite fields.
5. Click **Next** and review the import settings.
6. Click **Run** to start the import process | **Save and Run** to save the import settings for future use | **Save as and run** to save the import settings with a new name.

### Import Status (view status of your import) [link](https://5574610.app.netsuite.com/app/setup/upload/csv/csvstatus.nl?whence=) 

### Templates
- [Invoice](https://github.com/nt2311-vn/LabGroup_Netsuite/tree/main/CSVs/Invoice) 
- [Sales Order](https://github.com/nt2311-vn/LabGroup_Netsuite/tree/main/CSVs/Sales_Order)
- [Payment](https://github.com/nt2311-vn/LabGroup_Netsuite/tree/main/CSVs/Payment)
- [Credit Memo](https://github.com/nt2311-vn/LabGroup_Netsuite/tree/main/CSVs/Credit_memo)

### Utilities searches to get internalid
- [Get internalid of active customer](https://5574610.app.netsuite.com/app/common/search/searchresults.nl?searchid=2557&whence=)
- [Get item internalid](https://5574610.app.netsuite.com/app/common/search/searchresults.nl?searchid=1640&whence=)
- [Get location internalid](https://5574610.app.netsuite.com/app/common/otherlists/locationlist.nl?whence=) 
- [Get account by internalid](https://5574610.app.netsuite.com/app/accounting/account/accounts.nl?report=T&code=COA&whence=)
- [Get department internalid](https://5574610.app.netsuite.com/app/common/otherlists/departmentlist.nl?whence=)
- [Get bankname by internalid](https://5574610.app.netsuite.com/app/common/custom/custrecordentrylist.nl?rectype=341)
- [Get vendor by internalid](https://5574610.app.netsuite.com/app/common/search/searchresults.nl?searchid=1404&whence=)

### Utilities hard code list
- Special item cases

| Item         | Internalid |
|--------------|------------|
| Chênh lệch   | 229357     |
| AR-Corp      | 285636     |
| AR-Clinic    | 285635     |
| AR-Doc       | 285638     |
| AR-Insurance | 285637     |

- Order client type

|Type|Internalid|
|----|----------|
|Cash|1|
|Credit|2|

- Payment methods

|Method|Internalid|
|------|----------|
|MB Bank|9|
|ACB Bank|10|
