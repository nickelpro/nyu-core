THIS OUTLINE IS INCOMPLETE

# Instruction Cache #
(Verilog module known as Con_Instruction_Cache)

## Contents
* [Inputs](#inputs)
* [Outputs](#outputs)
* [Modules](#modules)
  * [Instruction Cache Manager](#instruction_cache_manager)
  * [L1 Instruction Cache](#l1_instruction_cache)
* [Internal Connections](#internal_connections)

## Inputs
|Name|Bits wide|
|:---|:---:|
|```cache_clk```|1-bit|
|```rstn```|1-bit|
|```pc```|32-bit|
|```mem_response_data```|32-bit|
|```mem_busy```|1-bit|

## Outputs
|Name|Bits wide|
|:---|:---:|
|```ins```|32-bit|
|```wEn```|1-bit|
|```rEn```|1-bit|
|```isBurst```|1-bit|
|```mem_address```|32-bit|
|```mem_write_data```|32-bit|

## Modules

### Instruction Cache Manager

#### External IO

##### External Inputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

##### External Outputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

#### Internal IO

##### Internal Inputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

##### Internal Outputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

### L1 Instruction Cache

#### External IO

##### External Inputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

##### External Outputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

#### Internal IO

##### Internal Inputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

##### Internal Outputs
|Name|Bits wide|
|:---:|:---:|
|```name```|#-bit|
|```name```|#-bit|

## Internal Connections

|Module 1|Module 2|Module N|
|:---:|:---:|:---:|
|```name```|```name```|```name```|
|```name```|```name```|```name```|
|```name```|```name```|```name```|
|```name```|```name```|```name```|
