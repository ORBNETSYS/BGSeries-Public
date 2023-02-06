# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

## [1.0.3] - 06.02.2023

- Fixed: Resolved a bug on new versions of Milestone versions where all point state would be set to "unassigned". 
- Changed: Logging of bypassed point states only when changes occur instead of logging all point states every 5 seconds.

## [1.0.2] - 16.06.2022

- TODO Fixed xml serialization error
- TODO Fixed question marks on output
- Fixed area icon blinking not setting the icon to the correct one at the end.
- Fixed point events firing when the state wasn't changed

## [1.0.1] - 02.05.2022

- Added: Public test application to test connections the B/G Panels using the Mode2 protocol.
- Changed: Read/write timeout on TCP connections changed from 5s to 30s to allow slower panels time to initiate the SSL connection.

