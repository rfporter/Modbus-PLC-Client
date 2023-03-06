# Modbus PLC Client

Extension to the Plasmionique Modbus Master, bringing Modicon-style data addressing and extended data type support.

To read or write to the PLC, simply use "MB Read.vim" or "MB Write.vim". Data conversion and function code selection is done internally.

This class is can to be overriden for your actual device.

Overrides:
- Initialize
- Poll *Required*
- Close
- Destruct