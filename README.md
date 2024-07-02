# KP8B
The Krypton Pi 8B CPU + info <br />
Made by Slicudis (@slicudis) <br />

ISA: https://docs.google.com/spreadsheets/d/1Fsal-7lGGJrTdmGC1KN0GybIsEcmk3nlsvMwRli7-7s/edit?usp=sharing <br />
Assembler: https://github.com/ProtoSebastian/newcpu <br />

Supported by (discord usernames): <br />
@protouncreative (Seb) [Creator of the assembler] <br />
@nioquis4321 (Ñoquis) [Making the simulator] <br />
@lorddecapo (Lord Decapo) <br />
@cane4123123 (Cane) <br />
@nioruff (Nioruff) <br />

Mapping of Siliconis-1: <br />
0000-1FFF: ROM <br />
2000-7FFF: RAM <br />
8000: Terminal <br />
8001: Keyboard <br />
8002-8004: Input and output ports <br />

Mapping of the computer used as an example: (KP8B file, not KP8B_CPU) <br />
FFF3: Pixel position (display) <br />
FFF4: Color in (display)  [Clear in fetching mode] <br />
FFF5-FFF7: Storage address <br />
FFFB: Dip switch <br />
FFFC: Hex-Binary display (low) <br />
FFFD: Hex-Binary display (high) <br />
FFFE: Terminal <br />
FFFF: Keyboard <br />
