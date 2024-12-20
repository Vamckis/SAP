# SAP - Systems Applications Products in DataProcessing
SAP is an ERP application (Enterprise Resource Planning), contains 80+ modules. SAP mmodules are 2 types:
- Functional Modules
  - SAP MM
  - SAP HR
  - SAP QM
  - SAP FICO
  - SAP PP
  - SAP SD
- Technical Modules
  - SAP ABAP (Advanced Business Application Programming) : Developers
  - SAP BASIS : Performs System Adminstartion activites
    - Software installations
    - System connections
    - Background jobs running
    - System issues
    - Troubleshooting
  - SAP Security
    - Account creation
    - Credentials management
    - Access provisioning to users (End users / IT users)

### SAP Architecture contains three layers:
- Presentation Layer : It is UI software (SAP GUI)
- Application Layer : It is processing machine of SAP. It contains Process and Services
  - Process
    - Dialog : All the interactions between User and System.
    - Background : Long duration activities and recurring activities.
    - Spool : print related activities.
    - Update : Updating DB - Create, Modify or Delete data.
    - Enqueue : Following Q while updating DB, to avoid deadlock situation
  - Services
    - Message : Load balancing among app servers.
    - Gateway : Communication channel between 2 SAP systems or 1 SAP to 1 Non-SAP service.
- Database Layer

### SAP Landscape
- Generally there wil be 3 System Landscapes:
  - Development System 
  - Quality System
  - Production systems

### SAP System (System IDs)
  - SAP Finance (FD1, FQ1, FP1)
  - SAP HR (HD1, HQ1, HP1)
  - SAP Sales Distribution (SD1, SQ1, SP1)
  - SAP CRM (CD1, CQ1, CP1)
  - SAP ECC (ED1, EQ1, EP1)
  - SAP GRC (GD1, GQ1, GP1)
  - SAP BI (BD1, BQ1, BP1)
- Basis, Security and ABAP are technical and admin teams
- Basis team will create Clients using Tcodes-SCC (Supply Chain Collaboration).
  - scc4 : To create a client and open SAP environment in edit mode. It Copies data from standard client to other clients.
  - scc5 : To delete a client.
  - sccl : Local client copy. Copy client within same SAP system.
  - scc9 : Remote client copy. Copy a client between two systems using an RFC connection.

### Client
- Partitions are made in SAP Hana to categorize data, called as clients (000 to 999) 
- Standard clients / Non IDES clients (International Demonstration and Education System)
  - 000
  - 001
  - 006
- IDES clients: Systems for Educational purposes
  - 800
  - 810
  - 811
  - 812

#### Client Independent & Dependent Data
- Individual Users are client dependent. Need not be in all clients.
- Background/Business users are client independent, available in all clients.

- sm50 : To view Work Processes
  ![image](https://github.com/user-attachments/assets/a1ecf8e0-524b-4046-a249-7bdeecab2b2a)
