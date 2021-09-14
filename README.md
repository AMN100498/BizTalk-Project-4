# BizTalk-Project-4

>> "OrderEntry.sln" is the VS2019 solution that contains the orchestration that is used to send a file to the web service and receive a response.

>> "CreatingFlatFiles.sln" is the VS2019 solution that contains the orchestration that has been exposed as a web service, "CreatingFlatFiles.odx" 
    in the CreatingFlatFiles project.
    - Within this solution there are three projects, none of which need to be changed; OrderSchema (contains all schemas and maps of the solution),             CreatingFlatFiles (main project), and CalculateTotalPrice (used in calculating values of Item Count and Total Order Price).
  
>> "tempuri.org.wsdl" is the WSDL code of the web service. Since the service is on my local machine, you will not be able to access it.

>> "TEST.xml" is the test file to be dropped into a file location.
