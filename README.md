# A2LReader
Parse the A2L format -- ASAM MCD-2 MC (aka ASAP2), defining the description format of the internal ECU variables used in measurement and calibration

A2L是ASAM MCD-2 MC Language的缩写。如果没有在A2L文件中定义编码，默认使用ISO-8859-1 (Latin-1) 。

|Top-Level Keyword  |	Description |
|:---------------   |:-------     |
|HEADER |	Allows to specify a project number and an ECU software version, for which the a2l-file is compatible with.  |
|MODULE |	Contains the data description for one ECU.  |
|PROJECT  |	Keyword on root level of the a2l-file. Contains everything. |
|A2ML_VERSION | Version of the ASAM MCD-2 MC meta language (AML) used in this file. |
|ASAP2_VERSION  |	Version of the ASAM MCD-2 MC standard used in this file.  |
