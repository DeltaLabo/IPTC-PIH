Command list for IPTC SCPI usage
============

## Standar commands
|SCPI Command | Description | Command Ex |
|---|---|---|
MEASure Subcommands |  |  |
MEASure:VOLTage? | Measures and returns the average voltage at the sense location | MEAS:VOLT:? |
MEASure:CURRent? | Measures and returns the average current at the sense location | MEAS:CURR:? |
|---|---|---|
OUTPut Subcommands |  |  |
OUTPut:START | Enables the power processing circuitry in the product to begin producing output | OUTP:START |
OUTPut:STOP | Disables the power processing circuitry in the product to stop producing output | OUTP:STOP |
|---|---|---|
SOURce Subcommands |  |  |
VOLTage | Sets the voltage set-point | VOLT 2500(mv) |
CURRent | Sets the current set-point | CURR 750 (mA) |
VOLTage:PROTection | Sets the voltage upper limit | VOLT:PROT 4200 (mV) |
CURRent:PROTection | Sets the current upper limit | CURR:PROT 3500 (mA) |

## Personal commands
|SCPI Command | Description | Command Ex |
|---|---|---|
MODE Subcommands |  |  |
MODE:CHARge | Sets the equipment into charge mode | MODE:CHAR |
MODE:DISCharge | Sets the equipment into discharge mode | MODE:DISC |
|---|---|---|
MODE CONFigure Subcommands |  |  |
VOLTage:ENDCharge | Sets the EOC voltage | VOLT:ENDC 1200 (mv) |
CURRent:ENDCharge | Sets the EOC current | CURR:ENDC 400 (mA) |
VOLTage:ENDDischarge | Sets the EOD voltage | VOLT:ENDD 400 (mV) |
|---|---|---|
CONFigure Subcommands |  |  |
CONFigure:CVKP | Configures the CV_kp variable | CONF:CVKP 1800 (xE-6) |
CONFigure:CVKI | Configures the CV_ki variable | CONF:CVKI 500 (xE-6) |
CONFigure:CVKD | Configures the CV_kd variable | CONF:CVKD 20 (xE-3) |
CONFigure:CCCP | Configures the CC_char_kp variable | CONF:CCCP 3000 (xE-6) |
CONFigure:CCCI | Configures the CC_char_ki variable | CONF:CCCI 50 (xE-6) |
CONFigure:CCDP | Configures the CC_char_kp variable | CONF:CCDP 6000 (xE-6) |
CONFigure:CCDI | Configures the CC_char_ki variable | CONF:CCDI 1000 (xE-6) |
