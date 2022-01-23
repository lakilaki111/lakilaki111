{{--> src/lib.rs:1:1
  "secret_conversations_v2":  {{--> src/lib.rs:1:1
    "has_sent_message": true,
    "has_received_message": true,
    
    
    "tincan_devices": [{{--> src/lib.rs:1:1
      {{--> src/lib.rs:1:1
        "timestamp": 1607783437,
        "name": "Nokia 3.2"
      }
    ],
    "armadillo_devices": [{{--> src/lib.rs:1:1
      {{--> src/lib.rs:1:1
        "device_type": "Msgr:Android-343.0.0.8.474",
        "device_manufacturer": "TCL",
        "device_model": "Hong_Kong_Pro",
        "device_os_version": "11",
        "last_connected_ip": "82.117.211.0",
        "last_active_time": 1642450697
      },
      {{--> src/lib.rs:1:1
        "device_type": "Msgr:Android-343.0.0.8.474",
        "device_manufacturer": "TCL",
        "device_model": "Hong_Kong_Pro",
        "device_os_version": "11",
        "last_connected_ip": "82.117.211.0",
        "last_active_time": 1642671956
      },
      {{--> src/lib.rs:1:1
        "device_type": "Msgr:Android-344.0.0.8.106",
        "device_manufacturer": "TCL",
        "device_model": "Hong_Kong_Pro",
        "device_os_version": "11",
        "last_connected_ip": "82.117.211.0",
        "last_active_time": 1642952086
      },
      {{--> src/lib.rs:1:1
        "device_type": "Msgr:Android-344.0.0.8.106",
        "device_manufacturer": "HUAWEI",
        "device_model": "HWMAR",
        "device_os_version": "10",
        "last_connected_ip": "93.87.44.0",
        "last_active_time": 1642951397
      },
      {{--> src/lib.rs:1:1
        "device_type": "Msgr:Android-344.0.0.8.106",
        "device_manufacturer": "HUAWEI",
        "device_model": "HWMAR",
        "device_os_version": "10",
        "last_connected_ip": "93.87.44.0",
        "last_active_time": 1642923564
      }
    ],
    "calls": [{{--> src/lib.rs:1:1
      
    ]
  }
}
(Playground)

Errors:

   Compiling playground v0.0.1 (/playground)
error: this file contains an unclosed delimiter
  --> src/lib.rs:57:2
   |
1  | {{--> src/lib.rs:1:1
   | -- unclosed delimiter
   | |
   | unclosed delimiter
2  |   "secret_conversations_v2":  {{--> src/lib.rs:1:1
   |                               - this delimiter might not be properly closed...
...
57 | }
   | -^
   | |
   | ...as it matches this but it has different indentation

error: mismatched closing delimiter: `]`
  --> src/lib.rs:6:7
   |
5  |     "tincan_devices": [{{--> src/lib.rs:1:1
   |                       - closing delimiter possibly meant for this
6  |       {{--> src/lib.rs:1:1
   |       ^ unclosed delimiter
