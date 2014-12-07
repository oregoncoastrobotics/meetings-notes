meetings-notes
==============
12-7-14
Meeting Notes

Daniel suggested writing common software (or at least api's) to use as an interface between arduinos and "higher level" processors, and between those processors and the LAN.  The intent of this software is that with some easy configuration it would be useful to many different robots and processors.

Wil suggested using GitHub for project collaboration.

Wil clarified that rather than re-invent the wheel, we should use already written software for complex functions (face recognition, navigation, etc...)


Wil talked about wanting another way to power up his robot (currently only 9v AA battery pack powered)
  Daniel suggested one possibility of:
    - 9v - Castle Creations 10A 6s Switchung Regulator: ~$20
      http://www.ebay.com/itm/Castle-Creations-CC-BEC-10A-6S-Switching-Regulator-FREE-SHIPPING-CSE095-0022-00-/151045421848?pt=Radio_Control_Parts_Accessories&hash=item232b023b18
      
      This regulator would allow a lithium polymer battery to be attached of between 3 and 6 cells
      
      Another option: ~$2
      http://www.ebay.com/itm/NEW-DC-4V-38V-to-1-25V-36V-5A-Step-Down-Power-Supply-Buck-Module-24V-12V-9V-5V-/271359649915?pt=LH_DefaultDomain_0&hash=item3f2e4ba87b

      this would require monitoring the battery voltage and automatically shutting down when voltage gets too low (over discharging lithium batteries destroys them)

      Example Battery:
        http://www.ebay.com/itm/Zop-Power-10000mAh-11-1V-Li-po-Lipo-Battery-For-Drift-Car-Align-RC-Helicopter-/351194954267?pt=Radio_Control_Parts_Accessories&hash=item51c4d9ba1b

      One could also purchase a plug-in power supply for testing only
      
      
It was decided that camera streaming and discrete (on/off) control were the top priorities in the near term.
