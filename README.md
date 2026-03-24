# nsx-cmsis-startup

`nsx-cmsis-startup` builds the board-selected startup and system sources needed
to boot an NSX bare-metal application.

The actual source files are provided by the selected board and SDK provider. This
module supplies the shared CMake target shape and export surface used by generated
apps.
