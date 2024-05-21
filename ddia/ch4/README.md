### Chapter 4: Encoding and Evolution

The main purpose of this section is to go over DDIA's chapter 4: Encoding and Evolution.

This part of the project is split up into 4 parts:

Thrift - Use Thrift for Backwards and Forwards compatibility

Avro - Use Avro for Backwards and Forwards compatibility

Protobuf - Use Protobuf for Backwards and Forwards compatibility

Finally, 

Json - Use JSON and other binary-ish methods for backwards and forwards compatibility

### Defining Forwards and Backwards compatibility

As in the book,

Forwards compatibility -> The ability for new code to read old encoded data

Backwards compatibility -> The ability for 

These together allow for schema evolution. 

For the purposes of testing changes, I will use the schema defined for iot-infra: https://github.com/onegules/iot_infra
