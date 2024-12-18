# `dmidecode` (Teamgroup Memory)

```bash
# dmidecode 3.4
Getting SMBIOS data from sysfs.
SMBIOS 2.6 present.
67 structures occupying 2576 bytes.
Table at 0xBAA9C000.

Handle 0x0000, DMI type 134, 16 bytes
OEM-specific Type
	Header and Data:
		86 10 00 00 00 53 54 4D 20 01 01 00 00 03 01 02
	Strings:
		TPM INFO
		System Reserved

Handle 0x0001, DMI type 4, 42 bytes
Processor Information
	Socket Designation: CPU
	Type: Central Processor
	Family: Core i7
	Manufacturer: Intel(R) Corporation
	ID: A7 06 02 00 FF FB EB BF
	Signature: Type 0, Family 6, Model 42, Stepping 7
	Flags:
		FPU (Floating-point unit on-chip)
		VME (Virtual mode extension)
		DE (Debugging extension)
		PSE (Page size extension)
		TSC (Time stamp counter)
		MSR (Model specific registers)
		PAE (Physical address extension)
		MCE (Machine check exception)
		CX8 (CMPXCHG8 instruction supported)
		APIC (On-chip APIC hardware supported)
		SEP (Fast system call)
		MTRR (Memory type range registers)
		PGE (Page global enable)
		MCA (Machine check architecture)
		CMOV (Conditional move instruction supported)
		PAT (Page attribute table)
		PSE-36 (36-bit page size extension)
		CLFSH (CLFLUSH instruction supported)
		DS (Debug store)
		ACPI (ACPI supported)
		MMX (MMX technology supported)
		FXSR (FXSAVE and FXSTOR instructions supported)
		SSE (Streaming SIMD extensions)
		SSE2 (Streaming SIMD extensions 2)
		SS (Self-snoop)
		HTT (Multi-threading)
		TM (Thermal monitor supported)
		PBE (Pending break enabled)
	Version: Intel(R) Core(TM) i7-2760QM CPU @ 2.40GHz
	Voltage: 1.2 V
	External Clock: 100 MHz
	Max Speed: 2400 MHz
	Current Speed: 2400 MHz
	Status: Populated, Enabled
	Upgrade: ZIF Socket
	L1 Cache Handle: 0x0002
	L2 Cache Handle: 0x0003
	L3 Cache Handle: 0x0004
	Serial Number: Not Supported by CPU
	Asset Tag: None
	Part Number: None
	Core Count: 4
	Core Enabled: 4
	Thread Count: 8
	Characteristics:
		64-bit capable

Handle 0x0002, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L1-Cache
	Configuration: Enabled, Not Socketed, Level 1
	Operational Mode: Write Through
	Location: Internal
	Installed Size: 64 kB
	Maximum Size: 64 kB
	Supported SRAM Types:
		Synchronous
	Installed SRAM Type: Synchronous
	Speed: Unknown
	Error Correction Type: Single-bit ECC
	System Type: Data
	Associativity: 8-way Set-associative

Handle 0x0003, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L2-Cache
	Configuration: Enabled, Not Socketed, Level 2
	Operational Mode: Write Through
	Location: Internal
	Installed Size: 256 kB
	Maximum Size: 256 kB
	Supported SRAM Types:
		Synchronous
	Installed SRAM Type: Synchronous
	Speed: Unknown
	Error Correction Type: Single-bit ECC
	System Type: Data
	Associativity: 8-way Set-associative

Handle 0x0004, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L3-Cache
	Configuration: Enabled, Not Socketed, Level 3
	Operational Mode: Write Back
	Location: Internal
	Installed Size: 6 MB
	Maximum Size: 6 MB
	Supported SRAM Types:
		Synchronous
	Installed SRAM Type: Synchronous
	Speed: Unknown
	Error Correction Type: Single-bit ECC
	System Type: Unified
	Associativity: 12-way Set-associative

Handle 0x0005, DMI type 16, 15 bytes
Physical Memory Array
	Location: System Board Or Motherboard
	Use: System Memory
	Error Correction Type: None
	Maximum Capacity: 32 GB
	Error Information Handle: Not Provided
	Number Of Devices: 4

Handle 0x0006, DMI type 17, 28 bytes
Memory Device
	Array Handle: 0x0005
	Error Information Handle: Not Provided
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelA-DIMM0
	Bank Locator: BANK 0
	Type: Unknown
	Type Detail: None

Handle 0x0007, DMI type 17, 28 bytes
Memory Device
	Array Handle: 0x0005
	Error Information Handle: Not Provided
	Total Width: 64 bits
	Data Width: 64 bits
	Size: 8 GB
	Form Factor: SODIMM
	Set: None
	Locator: ChannelA-DIMM1
	Bank Locator: BANK 1
	Type: DDR3
	Type Detail: Synchronous
	Speed: 1333 MT/s
	Manufacturer: 04EF
	Serial Number: 0202ACE5
	Asset Tag: 9876543210
	Part Number: TEAMGROUP-SD3-1600
	Rank: Unknown

Handle 0x0008, DMI type 17, 28 bytes
Memory Device
	Array Handle: 0x0005
	Error Information Handle: Not Provided
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelB-DIMM0
	Bank Locator: BANK 2
	Type: Unknown
	Type Detail: None

Handle 0x0009, DMI type 17, 28 bytes
Memory Device
	Array Handle: 0x0005
	Error Information Handle: Not Provided
	Total Width: 64 bits
	Data Width: 64 bits
	Size: 8 GB
	Form Factor: SODIMM
	Set: None
	Locator: ChannelB-DIMM1
	Bank Locator: BANK 3
	Type: DDR3
	Type Detail: Synchronous
	Speed: 1333 MT/s
	Manufacturer: 04EF
	Serial Number: 0202ACDA
	Asset Tag: 9876543210
	Part Number: TEAMGROUP-SD3-1600
	Rank: Unknown

Handle 0x000A, DMI type 19, 15 bytes
Memory Array Mapped Address
	Starting Address: 0x00000000000
	Ending Address: 0x003FFFFFFFF
	Range Size: 16 GB
	Physical Array Handle: 0x0005
	Partition Width: 4

Handle 0x000B, DMI type 129, 8 bytes
OEM-specific Type
	Header and Data:
		81 08 0B 00 01 01 02 01
	Strings:
		Intel_ASF
		Intel_ASF_001

Handle 0x000C, DMI type 130, 20 bytes
OEM-specific Type
	Header and Data:
		82 14 0C 00 24 41 4D 54 01 01 01 01 01 A5 FF 03
		00 00 01 00

Handle 0x000D, DMI type 131, 64 bytes
OEM-specific Type
	Header and Data:
		83 40 0D 00 3F 00 00 00 07 00 00 00 00 00 3F 00
		F8 00 4F 1C FF FF FF FF 09 E0 00 00 01 00 07 00
		C8 0C 5B 00 00 00 00 00 C8 00 02 15 00 00 00 00
		00 00 00 00 F6 00 00 00 76 50 72 6F 00 00 00 00

Handle 0x000E, DMI type 134, 13 bytes
OEM-specific Type
	Header and Data:
		86 0D 0E 00 14 06 12 20 00 00 00 00 00

Handle 0x000F, DMI type 0, 24 bytes
BIOS Information
	Vendor: LENOVO
	Version: 8BET66WW (1.46 )
	Release Date: 06/14/2018
	Address: 0xE0000
	Runtime Size: 128 kB
	ROM Size: 8 MB
	Characteristics:
		PCI is supported
		PNP is supported
		BIOS is upgradeable
		BIOS shadowing is allowed
		Boot from CD is supported
		Selectable boot is supported
		EDD is supported
		3.5"/720 kB floppy services are supported (int 13h)
		Print screen service is supported (int 5h)
		8042 keyboard services are supported (int 9h)
		Serial services are supported (int 14h)
		Printer services are supported (int 17h)
		CGA/mono video services are supported (int 10h)
		ACPI is supported
		USB legacy is supported
		BIOS boot specification is supported
		Targeted content distribution is supported
	BIOS Revision: 1.46
	Firmware Revision: 1.36

Handle 0x0010, DMI type 1, 27 bytes
System Information
	Manufacturer: LENOVO
	Product Name: 42763KU
	Version: ThinkPad W520
	Serial Number: R9PFND0
	UUID: a13b6081-51d8-11cb-81d6-a4deda156946
	Wake-up Type: Power Switch
	SKU Number: Not Specified
	Family: ThinkPad W520

Handle 0x0011, DMI type 2, 15 bytes
Base Board Information
	Manufacturer: LENOVO
	Product Name: 42763KU
	Version: Not Available
	Serial Number: 1ZKBX26C2ED
	Asset Tag: Not Available
	Features:
		Board is a hosting board
		Board is replaceable
	Location In Chassis: Not Available
	Chassis Handle: 0x0000
	Type: Motherboard
	Contained Object Handles: 0

Handle 0x0012, DMI type 3, 21 bytes
Chassis Information
	Manufacturer: LENOVO
	Type: Notebook
	Lock: Not Present
	Version: Not Available
	Serial Number: R9PFND0
	Asset Tag: No Asset Information
	Boot-up State: Unknown
	Power Supply State: Unknown
	Thermal State: Unknown
	Security Status: Unknown
	OEM Information: 0x00000000
	Height: Unspecified
	Number Of Power Cords: Unspecified
	Contained Elements: 0

Handle 0x0013, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: External Monitor
	External Connector Type: DB-15 female
	Port Type: Video Port

Handle 0x0014, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: DisplayPort
	External Connector Type: Other
	Port Type: Video Port

Handle 0x0015, DMI type 126, 9 bytes
Inactive

Handle 0x0016, DMI type 126, 9 bytes
Inactive

Handle 0x0017, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: Headphone/Microphone Combo Jack
	External Connector Type: Mini Jack (headphones)
	Port Type: Audio Port

Handle 0x0018, DMI type 126, 9 bytes
Inactive

Handle 0x0019, DMI type 126, 9 bytes
Inactive

Handle 0x001A, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: Ethernet
	External Connector Type: RJ-45
	Port Type: Network Port

Handle 0x001B, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: Modem
	External Connector Type: RJ-11
	Port Type: Modem Port

Handle 0x001C, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: USB 1
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x001D, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: USB 2
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x001E, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: USB 3
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x001F, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: Not Available
	Internal Connector Type: None
	External Reference Designator: USB/eSATA Combo
	External Connector Type: Other
	Port Type: Other

Handle 0x0020, DMI type 126, 9 bytes
Inactive

Handle 0x0021, DMI type 126, 9 bytes
Inactive

Handle 0x0022, DMI type 126, 9 bytes
Inactive

Handle 0x0023, DMI type 126, 9 bytes
Inactive

Handle 0x0024, DMI type 126, 9 bytes
Inactive

Handle 0x0025, DMI type 126, 9 bytes
Inactive

Handle 0x0026, DMI type 126, 9 bytes
Inactive

Handle 0x0027, DMI type 126, 9 bytes
Inactive

Handle 0x0028, DMI type 9, 17 bytes
System Slot Information
	Designation: ExpressCard Slot
	Type: x1 PCI Express
	Current Usage: Available
	Length: Other
	ID: 1
	Characteristics:
		Hot-plug devices are supported
	Bus Address: 0000:00:00.0

Handle 0x0029, DMI type 9, 17 bytes
System Slot Information
	Designation: Media Card Slot
	Type: Other
	Current Usage: Available
	Length: Other
	Characteristics:
		Hot-plug devices are supported
	Bus Address: 0000:00:00.0

Handle 0x002A, DMI type 126, 17 bytes
Inactive

Handle 0x002B, DMI type 10, 6 bytes
On Board Device Information
	Type: Other
	Status: Enabled
	Description: IBM Embedded Security hardware

Handle 0x002C, DMI type 12, 5 bytes
System Configuration Options

Handle 0x002D, DMI type 13, 22 bytes
BIOS Language Information
	Language Description Format: Abbreviated
	Installable Languages: 1
		en-US
	Currently Installed Language: en-US

Handle 0x002E, DMI type 22, 26 bytes
Portable Battery
	Location: Rear
	Manufacturer: SANYO
	Name: 42T4799
	Design Capacity: 93240 mWh
	Design Voltage: 11100 mV
	SBDS Version: 03.01
	Maximum Error: Unknown
	SBDS Serial Number: 558F
	SBDS Manufacture Date: 2012-03-02
	SBDS Chemistry: LION
	OEM-specific Information: 0x00000000

Handle 0x002F, DMI type 126, 26 bytes
Inactive

Handle 0x0030, DMI type 18, 23 bytes
32-bit Memory Error Information
	Type: OK
	Granularity: Unknown
	Operation: Unknown
	Vendor Syndrome: Unknown
	Memory Array Address: Unknown
	Device Address: Unknown
	Resolution: Unknown

Handle 0x0031, DMI type 21, 7 bytes
Built-in Pointing Device
	Type: Track Point
	Interface: PS/2
	Buttons: 3

Handle 0x0032, DMI type 21, 7 bytes
Built-in Pointing Device
	Type: Touch Pad
	Interface: PS/2
	Buttons: 2

Handle 0x0033, DMI type 131, 22 bytes
ThinkVantage Technologies
	Version: 1
	Diagnostics: No

Handle 0x0034, DMI type 136, 6 bytes
OEM-specific Type
	Header and Data:
		88 06 34 00 5A 5A

Handle 0x0035, DMI type 135, 74 bytes
OEM-specific Type
	Header and Data:
		87 4A 35 00 54 50 07 02 42 41 59 20 49 2F 4F 20
		02 00 06 FF 00 00 00 00 00 00 00 FF 00 00 00 00
		00 00 00 FF 00 00 00 00 00 00 00 FF 00 00 00 00
		00 00 00 FF 00 00 00 00 00 00 00 FF 00 00 00 00
		00 00 00 06 00 02 01 03 03 FF

Handle 0x0036, DMI type 140, 19 bytes
OEM-specific Type
	Header and Data:
		8C 13 36 00 4C 45 4E 4F 56 4F 0B 05 01 07 00 00
		00 00 00

Handle 0x0037, DMI type 140, 23 bytes
OEM-specific Type
	Header and Data:
		8C 17 37 00 4C 45 4E 4F 56 4F 0B 06 01 7E 14 00
		00 00 00 00 00 00 00

Handle 0x0038, DMI type 133, 5 bytes
OEM-specific Type
	Header and Data:
		85 05 38 00 01
	Strings:
		KHOIHGIUCCHHII

Handle 0x0039, DMI type 15, 29 bytes
System Event Log
	Area Length: 50 bytes
	Header Start Offset: 0x0000
	Header Length: 16 bytes
	Data Start Offset: 0x0010
	Access Method: General-purpose non-volatile data functions
	Access Address: 0x00F0
	Status: Valid, Not Full
	Change Token: 0x00000002
	Header Format: Type 1
	Supported Log Type Descriptors: 3
	Descriptor 1: POST error
	Data Format 1: POST results bitmap
	Descriptor 2: Single-bit ECC memory error
	Data Format 2: Multiple-event
	Descriptor 3: Multi-bit ECC memory error
	Data Format 3: Multiple-event

Handle 0x003A, DMI type 140, 67 bytes
OEM-specific Type
	Header and Data:
		8C 43 3A 00 4C 45 4E 4F 56 4F 0B 00 01 98 0A 1E
		42 02 AE B4 6F 3B 6F 90 1D 89 03 AE AD 01 00 00
		00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
		00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
		00 00 00

Handle 0x003B, DMI type 140, 47 bytes
OEM-specific Type
	Header and Data:
		8C 2F 3B 00 4C 45 4E 4F 56 4F 0B 01 01 28 00 32
		B3 B2 08 F5 5F 73 80 5F 1B 3A 41 C6 71 C5 B9 00
		00 00 00 10 00 10 00 10 01 D0 00 20 01 00 01

Handle 0x003C, DMI type 140, 63 bytes
OEM-specific Type
	Header and Data:
		8C 3F 3C 00 4C 45 4E 4F 56 4F 0B 02 01 00 00 00
		00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
		00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
		00 00 00 00 00 00 00 00 00 00 00 00 00 00 00

Handle 0x003D, DMI type 140, 17 bytes
OEM-specific Type
	Header and Data:
		8C 11 3D 00 4C 45 4E 4F 56 4F 0B 03 01 00 00 00
		00

Handle 0x003E, DMI type 140, 19 bytes
OEM-specific Type
	Header and Data:
		8C 13 3E 00 4C 45 4E 4F 56 4F 0B 04 01 B2 00 4D
		53 20 00

Handle 0x003F, DMI type 24, 5 bytes
Hardware Security
	Power-On Password Status: Disabled
	Keyboard Password Status: Not Implemented
	Administrator Password Status: Disabled
	Front Panel Reset Status: Not Implemented

Handle 0x0040, DMI type 132, 7 bytes
OEM-specific Type
	Header and Data:
		84 07 40 00 01 D8 36

Handle 0x0041, DMI type 135, 18 bytes
OEM-specific Type
	Header and Data:
		87 12 41 00 54 50 07 01 01 C9 07 00 00 00 06 00
		00 00

Handle 0xFEFF, DMI type 127, 4 bytes
End Of Table
```
