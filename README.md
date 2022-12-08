# Common Information Model for Robot Modules

- License of source code is avaiable in https://github.com/informationModel/commonModules/wiki/License-the-editor-of-CIM-for-robot-modules <br>
  . Built Code: CIM Editor 0.9.1 <br>
  . Source Code: Common Information Model 20221031
  
## Describe common information for modules
- Module with hardware aspect and software aspect (Abbreviation: HWSW module)
- Module with only hardware aspects(Abbreviation: HW module)
- Module with only software aspects(Abbreviation: SW module)

## Common information
- Based on template in Annex A of ISO 22166-1

  . Provided rough information
- Provided in XML by module developer/manufacturer/designer/integrator
- Used for rough integration/connection of modules

  . Detailed information should be provided in lower information model such as 202, 203, and 3xx.
- Describe functions/interfaces provided by modules but not used by modules

  . From viewpoint of producer and consumer

## Information model for SW aspects and HW aspects:

Provide the detailed information such as
- Operating environments/conditions
- Interface type

  . According to Module type
  
      Mechanical inteface
      Electrical Interface
      Software Interface
   
  . According to Shape or Role
  
      Female and Male  for Mechanical and Elec. Ifs.    
      Provided(provider) and required(consumer) for SW IFs
- Interface pose/size if necessary

Used for check the interconnection and invoke the services
