# Bluetooth low energy equipment

BLE measurement equipment can be sorted in two kinds. Telink prepares some documents here which are helpful for customers to verify their boards.

### Non-signaling

One kind is named as non-signaling equipment. It means PC is the control center, it controls equipment and dut respectively.When the equipment acts as a signal generator, dut acts as a receiver and gives the feedback to PC tool. When dut acts as a signal generator, the equipment acts as a receiver and shows the test result on PC tool.Some popular equipment are listed here.

1. Itest -	WT-200 | [WT-200 user guide](http://wiki.telink-semi.cn/doc/an/AN_19032100-E_WT-200%20Guide%20on%20Testing%20Telink%20BLE%20Module.pdf)
2. Litepoint -	IQ2010
3. Anritsu -	MT8870A

### Signaling

The other kind is named as signaling equipment. It means PC only controls equipment, dut is plugged in equipment and doesn't communicate with PC directly. So operater only uses PC tool to control equipment and get the measurement result.

1. R&S -	CMW270/CMW500
2. Anritsu -	MT8852B | [MT8852B user guide](http://wiki.telink-semi.cn/doc/an/AN_BLE-16032100-E_Telink%20BLE%20PHY%20Test%20Manual.pdf)
