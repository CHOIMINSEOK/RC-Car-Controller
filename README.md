
RC-Car Controller with Bluetooth Module
===================================

Implement RC-Car Controller Based on Google Bluetooth Sample.
all the fundamental Bluetooth API capabilities.

Introduction
------------

This should be run on Android device with `HC-06` Bluetooth Module RC-Car at the same time, to establish conversation
Bluetooth between the devices. Select "Made discoverable" in overflow menu on one device and click
on the Bluetooth icon on the other one, to find the device and establish the connection.

The sample demonstrates the following, using the [Bluetooth API][1]:

1. [Setting up][2] Bluetooth
2. [Scanning][3] for other Bluetooth devices
3. [Querying][4] the local Bluetooth adapter for paired Bluetooth devices
4. [Establishing RFCOMM][5] channels/sockets
5. [Connecting][6] to a remote device
6. [Transfering][7] data over Bluetooth

[1]: http://developer.android.com/guide/topics/connectivity/bluetooth.html
[2]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#Permissions
[3]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#FindingDevices
[4]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#QueryingPairedDevices
[5]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#ConnectingDevices
[6]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#ConnectingAsAClient
[7]: http://developer.android.com/guide/topics/connectivity/bluetooth.html#ManagingAConnection

Pre-requisites
--------------

- Android SDK 26
- Android Build Tools v27.0.2
- Android Support Repository



License
-------

Copyright 2017 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
