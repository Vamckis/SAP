# SAP Architecture
SAP Architecture contains three layers:
- Presentation Layer : It is UI software (SAP GUI)
- Application Layer : It is processing machine of SAP. It contains Process and Services
  - Process
    - Dialog : All the interactions between User and System
    - Background : Long duraion activities and recurring activities
    - Spool : print rekated activities
    - Update : Updating DB - Create, Modify or Delete data
    - Enqueue : Following Q while updating DB, to avaoid deadlock situation
  - Services
    - Message : Load balancing among app servers
    - Gateway : Communication channel between 2 SAP systems or 1 SAP to 1 Non-SAP service
- Database Layer
### SAP Landscape
- Generally there wil be 3 System Landscapes:
  - Developments
  - Quality
  - Production systems
- Below are some SAP functional modules
  - SAP Finance (FD1, FQ1, FP1)
  - SAP HR (HD1, HQ1, HP1)
  - SAP Sales (SD1, SQ1, SP1)
  - SAP CRM (CD1, CQ1, CP1)
  - SAP ECC (ED1, EQ1, EP1)
- Basis, Security and ABAP are technical and admin teams
