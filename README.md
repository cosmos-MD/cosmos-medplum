This is a fork of github.com/medplum - we will look to contribute our work upstream and minimize the "fork" deltas, meanwhile provides a stable point to develop cosmosMD solutions from. 
Refer to https://www.medplum.com/docs/contributing/run-the-stack

#### Folder structure

```sh
medplum/
├── packages
│   ├── agent        # On-premise agent
│   ├── app          # Frontend web app
│   ├── bot-layer    # AWS Lambda Layer for Bots
│   ├── cdk          # AWS CDK infra as code
│   ├── cli          # Command line interface
│   ├── core         # Core shared library
│   ├── definitions  # Data definitions
│   ├── docs         # Documentation
│   ├── examples     # Example code used in documentation
│   ├── fhir-router  # FHIR URL router
│   ├── fhirtypes    # FHIR TypeScript definitions
│   ├── generator    # Code generator utilities
│   ├── graphiql     # Preconfigured GraphiQL
│   ├── hl7          # HL7 client and server
│   ├── mock         # Mock FHIR data for testing
│   ├── react        # React component library
│   └── server       # Backend API server
└── scripts          # Helper bash scripts
```

## License

[Apache 2.0](LICENSE.txt)

Copyright &copy; Medplum 2023

FHIR&reg; is a registered trademark of HL7.

SNOMED&reg; is a registered trademark of the International Health Terminology Standards Development Organisation.

LOINC&reg; is a registered trademark of Regenstrief Institute, Inc.

DICOM&reg; is the registered trademark of the National Electrical Manufacturers Association (NEMA).
