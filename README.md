# WEB SERVICE

## SOAP

### XML
XML: Extensible Markup Language

    <OrderId>123<OrderId/>
    <ShippingInfo>...<ShippingInfo/>

**Data**: 123 \
**Metadata**: OrderId [Info knows what to do with this data.]



#### When
1. Data Exchange \
2. Configuration File\
    web.xml\
    server.cml\
    pom.xml\
    build.xml \
3. Save Manipulate and Present

#### XSD .xsd

XSD: XML Schema Definition

XSD is a grammer of XML.\

1. Elements
2. Attributes
3. Namespaces
4. Order
5. Number of Occurrences
6. Restrictions

W3C: World Web Consortium

#### Namespace
Schema: 

    targetNamespace:
        http://www.amazon.com/order 
        http://www.ebay.com/order 
    prefix: 
        xmlns:amz = "http://www.amazon.com/order" 
        xmlns:ebay= "http://www.ebay.com/order"


XML:

    <order xmlns:amz="http://www.amazon.com/order">
        <amz:lineitem/>
        <amz:shippingaddress/>
    
    <order xmlns:amz="http://www.ebay.com/order">
        <amz:lineitem/>
        <amz:shippingaddress/>


## REST