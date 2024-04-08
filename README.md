# erp-api-controller routes list

### [erp-api-controller-acquisitions](https://github.com/one1erp/erp-api-controller-acquisitions "erp-api-controller-acquisitions")
**Routes:**
- **POST** `/firms/:firm_code/documents/acquisitions/demands ` - create demand
- **POST** `/firms/:firm_code/documents/acquisitions/orders ` - create order
- **PUT** `/firms/:firm_code/documents/acquisitions/demands/:document_number` - update demand
- **PUT** `/firms/:firm_code/documents/acquisitions/orders/:document_number` - update order

**Contributors:**[@Pesya1](https://github.com/Pesya1)

**Extended controller:**[erp-api-controller-acquisitions-kkl](https://github.com/one1erp/erp-api-controller-acquisitions-kkl "erp-api-controller-acquisitions-kkl")

### [erp-api-controller-acquisitions-kkl-old](https://github.com/one1erp/erp-api-controller-acquisitions-kkl-old "erp-api-controller-acquisitions-kkl-old")
**Routes:**
- **POST** `/firms/:firm_code/documents/acquisitions/orders ` - create order
- **PUT** `/firms/:firm_code/documents/acquisitions/orders/:document_number` - update order

**Contributors:**[@avigailc-one1](https://github.com/avigailc-one1)

### [erp-api-controller-acquisitions-tiv](https://github.com/one1erp/erp-api-controller-acquisitions-tiv "erp-api-controller-acquisitions-tiv")
**Routes:**
- **GET** `/firms/:firm_code/documents/acquisitions/requests ` - get acquisitions

**Contributors:**[@avigailc-one1](https://github.com/avigailc-one1)

### [erp-api-controller-api-users](https://github.com/one1erp/erp-api-controller-api-users "erp-api-controller-api-users")
**Routes:**
- **POST** `/api_users ` - create user
- **PUT** `/api_users/:id ` - update user
- **DELETE** `/api_users/:id ` - delete user
- **GET** `/api_users ` - get users list
- **GET** `/api_users/:id ` - view user details
- **POST** `/permissions` - create permission
- **GET** `/permissions` - get permissions
- **PUT** `/permissions/:id` - update permission
- **DELETE** `/permissions/:id` - delete permission
- **POST** `/permission_groups` - create permission group
- **GET** `/permission_groups` - get permissions group
- **PUT** `/permission_groups/:id` - update permission group
- **DELETE** `/permission_groups/:id` - delete permission group
- **GET** `/permission_groups/:id` - view permission group

**Contributors:**[@avigailc-one1](https://github.com/avigailc-one1)

### [erp-api-controller-contact-persons](https://github.com/one1erp/erp-api-controller-contact-persons "erp-api-controller-contact-persons")
**Routes:**
- **GET**`/firms/:firm_code/suppliers/:supplier_code/contact_persons` - get supplier contacts list
- **GET**`/firms/:firm_code/suppliers/:supplier_code/contact_persons/:contact_person_code` - view supplier contact person
- **POST**`/firms/:firm_code/suppliers/:supplier_code/contact_persons` - create supplier contact person
- **PUT**`/firms/:firm_code/suppliers/:supplier_code/contact_persons/:contact_person_code` - update supplier contact person
- **DELETE**`/firms/:firm_code/suppliers/:supplier_code/contact_persons/:contact_person_code` - delete supplier contact person
- **GET**`/firms/:firm_code/customers/:customer_code/contact_persons` - get customer contacts list
- **GET**`/firms/:firm_code/customers/:customer_code/contact_persons/:contact_person_code` - view customer contact person
- **POST**`/firms/:firm_code/customer/:customer_code/contact_persons` - create customer contact person
- **PUT**`/firms/:firm_code/customers/:customer_code/contact_persons/:contact_person_code` - update customer contact person
- **DELETE**`/firms/:firm_code/customers/:customer_code/contact_persons/:contact_person_code` - delete customer contact person

**Contributors:**[@Pesya1](https://github.com/Pesya1)


### [erp-api-controller-contacts](https://github.com/one1erp/erp-api-controller-contacts "erp-api-controller-contacts")
**Routes:**
- **GET**`/firms/:firm_code/customers/:customer_code/contacts` - get contacts

**Contributors:**[@Ayala](https://github.com/AyalapOne1)

### [erp-api-controller-customers](https://github.com/one1erp/erp-api-controller-customers "erp-api-controller-customers")
**Routes:**
- **POST** `/firms/:firm_code/customers ` - create customer
- **PUT** `/firms/:firm_code/customers/:customer_code` - update customer
- **POST**`/firms/:firm_code/customers/:customer_code/logistics` - create logistic customer
- **GET**`/firms/:firm_code/customers/:customer_code` - get customer**

**Contributors:**[@Pesya1](https://github.com/Pesya1)

**Extended controller:**[erp-api-controller-customers-supergas](https://github.com/one1erp/erp-api-controller-customers-supergas "erp-api-controller-customers-supergas")


### [erp-api-controller-customers-potentials](https://github.com/one1erp/erp-api-controller-customers-potentials "erp-api-controller-customers-potentials")
**Routes:**
- **POST**`/firms/:firm_code/customers/` - create customer
- **PUT**`/firms/:firm_code/customers/:customer_code` - update customer
- **POST**`/firms/:firm_code/customers/convertToObject` - convert customer

**Contributors:**[@Ayala](https://github.com/AyalapOne1), [@avigailc-one1](https://github.com/avigailc-one1), [@Pesya1](https://github.com/Pesya1)

### [erp-api-controller-inventory](https://github.com/one1erp/erp-api-controller-inventory "erp-api-controller-inventory")
**Routes:**
- **POST**`/firms/:firm_code/inventory/issue` - inventory issues
- **POST**`/firms/:firm_code/inventory/counting` - inventory counting

**Contributors:**[@avigailc-one1](https://github.com/avigailc-one1), [@Miriam](https://github.com/miriamPone1), [@Pesya1](https://github.com/Pesya1)

### [erp-api-controller-inventory-yaham](https://github.com/one1erp/erp-api-controller-inventory-yaham "erp-api-controller-inventory-yaham")
**Routes:**
- **POST**`/firms/:firm_code/work_order/:work_order_number ` - pallets issues

**Contributors:**[@Pesya1](https://github.com/Pesya1)

### [erp-api-controller-invoices](https://github.com/one1erp/erp-api-controller-invoices "erp-api-controller-invoices")
**Routes:**
- **POST**`/firms/:firm_code/customers/:customer_code/documents/shipping ` - create invoice 

**Contributors:**[@Avigail](https://github.com/avigailc-one1),  [@Ayala](https://github.com/AyalapOne1)

**Extended controller:**[erp-api-controller-invoices-agami](https://github.com/one1erp/erp-api-controller-invoices-agami "erp-api-controller-invoices-agami"), [erp-api-controller-invoices-berman](https://github.com/one1erp/erp-api-controller-invoices-berman "erp-api-controller-invoices-berman")

### [erp-api-controller-invoices-doralon](https://github.com/one1erp/erp-api-controller-invoices "erp-api-controller-invoices-doralon")
**Routes:**
- **GET**`/firms/:firm_code/customers/:customer_code/documents/invoices/:invoice_number/export` - get invoice document, file

**Contributors:**[@Pesya](https://github.com/Pesya1)


### [erp-api-controller-invoices-kalab](https://github.com/one1erp/erp-api-controller-invoices "erp-api-controller-invoices-kalab")
**Routes:**
- **POST**`/firms/:firm_code/invoices/:document_number/milestons` - register milestones

**Contributors:**[@Avigail](https://github.com/avigailc-one1)

### [erp-api-controller-invoices-kkl](https://github.com/one1erp/erp-api-controller-invoices "erp-api-controller-invoices-kkl")
**Routes:**
- **POST**`/firms/:firm_code/customers/:customer_code/documents/invoices` - create invoice
- **PUT**`/firms/:firm_code/customers/:customer_code/documents/invoices/:document_number` - update invoice

**Contributors:**[@Ayala](https://github.com/AyalapOne1)

### [erp-api-controller-invoices-payments-supergas](https://github.com/one1erp/erp-api-controller-invoices-payments-supergas")
**Routes:**
- **GET**`/firms/:firm_code/customers/:customer_code/documents/invoices/:invoice_number/balance` - get invoice informations
- **POST**`/firms/:firm_code/customers/:customer_code/documents/invoices/:invoice_number/payment` - create billing payment
- **POST**`/firms/:firm_code/customers/:customer_code/end_bill` - end bill

**Contributors:**[@Ayala](https://github.com/AyalapOne1), [@Miriam](https://github.com/miriamPone1)

### [erp-api-controller-orders](https://github.com/one1erp/erp-api-controller-orders "erp-api-controller-orders")
**Routes:**
- **POST**`/firms/:firm_code/customers/:customer_code/documents/orders ` - create order

**Contributors:**[@Ayala](https://github.com/AyalapOne1), [@Avigail](https://github.com/avigailc-one1)

**Extended controller:**[erp-api-controller-orders-kalab](https://github.com/one1erp/erp-api-controller-orders-kalab "erp-api-controller-orders-kalab")


### [erp-api-controller-orders-kkl](https://github.com/one1erp/erp-api-controller-orders-kkl "erp-api-controller-orders-kkl")
**Routes:**
- **POST**`/firms/:firm_code/customers/:customer_code/documents/orders ` - create order
- **PUT**`/firms/:firm_code/customers/:customer_code/documents/orders/:document_number ` - update order

**Contributors:**[@Avigail](https://github.com/avigailc-one1)



### [erp-api-controller-parts](https://github.com/one1erp/erp-api-controller-parts "erp-api-controller-parts")
**Routes:**
- **PUT**`/firms/:firm_code/parts/:part_code ` - update part_code

**Contributors:**[@Avigail](https://github.com/avigailc-one1)


### [erp-api-controller-quotas](https://github.com/one1erp/erp-api-controller-quotas "erp-api-controller-quotas")
**Routes:**
- **POST**`/firms/:firm_code/customers/:customer_code/quota ` - create quota for customer

**Contributors:**[@Ayala](https://github.com/AyalapOne1),[@Avigail](https://github.com/avigailc-one1),

**Extended controller:**[erp-api-controller-quotas-kalab](https://github.com/one1erp/erp-api-controller-quotas-kalab "quotas-kalab")

### [erp-api-controller-reports-doralon](https://github.com/one1erp/erp-api-controller-reports-doralon "erp-api-controller-reports-doralon")
**Routes:**
- **GET**`/firms/:firm_code/customers/:customer_code/reports ` - view report

**Contributors:**[@Pesya](https://github.com/Pesya1)


### [erp-api-controller-requests](https://github.com/one1erp/erp-api-controller-requests "erp-api-controller-requests")
**Routes:**
- **GET**`/firms/:firm_code/customers/:customer_code/requests ` - get customer requests
- **GET**`/firms/:firm_code/requests/systems/:system_number/case_types ` - get case types
- **POST**`/firms/:firm_code/customers/:customer_code/requests ` - create request
- **GET**`/firms/:firm_code/customers/:customer_code/requests/systems ` - get systems
- **GET**`/firms/:firm_code/requests/env_types ` - get env types

**Contributors:**[@Ayala](https://github.com/AyalapOne1)

### [erp-api-controller-suppliers-kkl](https://github.com/one1erp/erp-api-controller-suppliers-kkl "erp-api-controller-suppliers-kkl")
**Routes: **
- **POST**`/firms/:firm_code/suppliers ` - create supplier
- **PUT**`/firms/:firm_code/suppliers/:supplier_code ` - update supplier

**Contributors:**[@Ayala](https://github.com/AyalapOne1), [@Avigail](https://github.com/avigailc-one1)


### [erp-api-controller-suppliers-kkl-attachments](https://github.com/one1erp/erp-api-controller-suppliers-kkl-attachments "erp-api-controller-suppliers-kkl-attachments")
**Routes:**
- **POST**`/firms/:firm_code/suppliers/:supplier_code/attachments` - create attachment
- **GET**`/firms/:firm_code/suppliers/:supplier_code/attachments/:object_id ` - get attachment
- **GET**`/firms/:firm_code/suppliers/:supplier_code/attachments ` - get attachment list

**Contributors:**[@Avigail](https://github.com/avigailc-one1), [@Ayala](https://github.com/AyalapOne1)


### [erp-api-controller-suppliers-ratings-kkl](https://github.com/one1erp/erp-api-controller-suppliers-ratings-kkl "erp-api-controller-suppliers-ratings-kkl")
**Routes:**
- **POST**`/firms/:firm_code/suppliers/:supplier_code/ratings` - create rating
- **GET**`/firms/:firm_code/suppliers/:supplier_code/ratings ` - get ratings

**Contributors:**[@Ayala](https://github.com/AyalapOne1)

### [erp-api-controller-suppliers-sanctions-kkl](https://github.com/one1erp/erp-api-controller-suppliers-sanctions-kkl "erp-api-controller-suppliers-sanctions-kkl")
**Routes:**
- **POST**`/firms/:firm_code/suppliers/:supplier_code/sanctions` - create sanctions
- **PUT**`/firms/:firm_code/suppliers/:supplier_code/sanctions` - update sanction
- **GET**`/firms/:firm_code/suppliers/:supplier_code/sanctions ` - get sanctions

**Contributors:**[@Ayala](https://github.com/AyalapOne1)

### [erp-api-controller-tenders-kkl](https://github.com/one1erp/erp-api-controller-tenders-kkl "erp-api-controller-tenders-kkl")
**Routes:**
- **POST**`/firms/:firm_code/tenders` - create tender
- **PUT**`/firms/:firm_code/tenders/:tender_code` - update tender

**Contributors:**[@Avigail](https://github.com/avigailc-one1), [@Ayala](https://github.com/AyalapOne1)


### [erp-api-controller-transportation-kkl](https://github.com/one1erp/erp-api-controller-transportation-kkl "erp-api-controller-transportation-kkl")
**Routes:**
- **GET**`/firms/:firm_code/maximum_subsidy ` - get maximum subsidy

**Contributors:**[@Avigail](https://github.com/avigailc-one1)


### [erp-api-controller-users](https://github.com/one1erp/erp-api-controller-users "erp-api-controller-users")
**Routes:**
- **PUT**`/users/me ` - update password

**Contributors:**[@Ayala](https://github.com/AyalapOne1)
