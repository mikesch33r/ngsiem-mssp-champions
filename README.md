# NG-SIEM MSSP Champions Workshop Tools
<br/>
The NG-SIEM MSSP Champions program is intended to assist Service Providers as they onboard and deliver CrowdStrike NG-SIEM. This wiki repository contains some technical content as part of the workshop.<br/>
<br/>

If you are using a Mac and would like to set up NG-SIEM ingest of the MacOS unified log:
| MacOS  |  |
| ------------- | ------------- |
| [Mac Config](https://github.com/mikesch33r/ngsiem-mssp-champions/blob/main/macOS/macos-unifiedlog-config.yaml)  | The local logscale collector configuration file, pre-formatted for you  |
| [Mac Parser](https://github.com/mikesch33r/ngsiem-mssp-champions/blob/main/macOS/macos-unifiedlog-parser.yaml)  | The appropriate parser that the HEC connector will use to parse the unified logs  |
<br/>

If you are using a Windows host and would like to set up NG-SIEM ingest of the Windows event log:
| Windows  |  |
| ------------- | ------------- |
| [Windows Config](https://github.com/mikesch33r/ngsiem-mssp-champions/blob/main/windows/windows-eventlog-config.yaml)  | The local logscale collector configuration file, pre-formatted for you  |
| Windows Parser  | There is already a Windows parser in NG-SIEM called "microsoft-windows" [US1](https://falcon.crowdstrike.com/data-connectors/parsers/IZ0Wb4GpqyLbiuNomuZeLo9uxQrWJ96i/details) US2(https://falcon.us-2.crowdstrike.com/data-connectors/parsers/IZ0Wb4GpqyLbiuNomuZeLo9uxQrWJ96i/details) |
