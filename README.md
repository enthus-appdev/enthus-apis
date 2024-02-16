### Buf

[Install Buf](https://buf.build/docs/installation/).

Run `buf generate proto` to generate the necessary code based on protobuf.


### Create or Update protofiles

- Create or change the .proto files you need
- run `buf generate` to create/update the files
- navigate to the `gen/go/stargate` folder and copy it
- open your local API repo and search for the `gen` folder
- delete the existing `stargate` folder and paste the `stargate` folder you copied earlier

### Testing with Postman

- start your local stargate and open [Postman](https://enthus.postman.co/workspace/MTS~03637d57-aee3-47fa-b8d3-6a3ea0678287/grpc-request/65326589ee1f5cf9a16bd202)
