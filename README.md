# Activation-Lookup-Tables
The two activation fuctions Sigmoid and Tanh are implemented on software using look-up tables. To reduce on-memory storage of SoC, we migrated lookup Tables from being on software to hardware.
The code is avaiable   here for [sigmoid](https://github.com/ashrakatkh/Activation-Lookup-Tables/blob/main/sigmoid.v) and [Tanh](https://github.com/ashrakatkh/Activation-Lookup-Tables/blob/main/tanh.v)
 ## Analysis
|property             | Tanh | Sigmoid|
| :---                | :---:|   ---: |
| gates no.           | 226  | 198    |
| memory saved (bits) | 2048 | 2048   |
 
